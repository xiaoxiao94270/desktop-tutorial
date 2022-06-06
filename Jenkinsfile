node {
        stage('clone') { 
		git 'https://github.com/xiaoxiao94270/desktop-tutorial.git'

        }
        stage('build') { 
                sh label: '', script: 'javac Main.java' 
        }
        stage('run') { 
                sh label: '', script: 'java Main'
        }
}
