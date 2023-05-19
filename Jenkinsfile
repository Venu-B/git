pipeline {
    // agent any
    agent {label "dev"}

    stages {
        stage('Build') {
            steps {
                echo 'Building by webhooks..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
