pipeline {
    // agent any
    agent {label "dev"}

    stages {
        stage('Build') {
            steps {
                echo 'Building by webhooks working fine..'
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
