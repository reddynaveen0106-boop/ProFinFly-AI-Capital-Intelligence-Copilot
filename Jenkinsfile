pipeline {
    agent any

    stages {
        stage('Create .env') {
            steps {
                sh '''
                cat > .env <<EOF
DATABASE_URL=postgresql://postgres:postgres123@postgres:5432/profinfly_ai
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
GEMINI_MODEL=gemini-flash-latest
EOF
                '''
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                docker compose down || true
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
