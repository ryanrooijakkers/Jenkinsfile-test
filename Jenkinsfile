// sh voor Linux en bat voor windows

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building in workspace: ${env.WORKSPACE}'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing build: ${env.BUILD_ID}'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}