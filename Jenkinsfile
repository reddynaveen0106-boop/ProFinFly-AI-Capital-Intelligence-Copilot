pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                cd /home/ubuntu/ProFinFly-AI-Capital-Intelligence-Copilot

                git pull origin main

                docker compose down
                docker compose up --build -d
                '''
            }
        }
    }

    post {
        success {
            echo 'Deployment Successful!'
        }
        failure {
            echo 'Deployment Failed!'
        }
    }
}
