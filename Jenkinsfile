pipeline {
    agent any
    stages {
        stage('Docker Version') {
            steps {
                script {
                    sh 'docker --version'
                }
            }
        }
        stage('Run Hello World') {
            steps {
                script {
                    sh 'docker run hello-world'
                }
            }
        }
    }
}
