node {
        stage('clone') { 
		git 'https://hithub.com/priximmo/jenkins-helloworld'

        }
        stage('build') { 
                sh "label: '', script: 'javac Main.java' 
        }
        stage('run') { 
                sh "label: '', script: 'java Main'
        }
}