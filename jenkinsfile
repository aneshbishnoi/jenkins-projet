pipeline {
    agent any

    stages {
        stage('run a command') {
            steps {
                sh '''
                ls
                date
                cal 2024
                '''
            }
        
        }
         stage('EnvirOment Veriables') {
            steps {
                sh 'echo "${BUILD_ID}"'
            }
        }
         stage('build') {
            steps {
                echo 'build'
            }
        }
         stage('Deploy on test') {
            steps {
                echo 'deploy to test'
            }
        }
         stage('Deploy on prod') {
            steps {
                echo 'deploy to prod'
            }
        }
    }
}
