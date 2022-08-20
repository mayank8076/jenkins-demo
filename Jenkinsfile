pipeline {
    agent any
    stages {
        stage('Version') {
            steps {
                script {
                    sh 'python3 --version'
                }
            }
        }
        
        stage('Hello') {
            steps {
                script {
                    sh 'python3 hello-world.py'
                }
            }
        }


    }
}
