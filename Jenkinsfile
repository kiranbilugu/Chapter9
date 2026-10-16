pipeline {
    agent any;
    stages {
        stage('Code quality') {
            steps {
                sh 'echo performing code quality checks'
            }
        }
        stage('Unit Tests') {
            steps {
                sh 'echo executing unit tests'
            }
        }
        stage('Build') {
            steps {
                sh 'echo building the application package'
            }
        }
        stage('Delivery') {
            steps {
                sh 'echo uploading artifact to the repository'
            }
        }
        stage('Deployment') {
            steps {
                sh 'echo deploying the application to the target environment'
            }
        }
    }
}
