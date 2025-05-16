pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git credentialsId: 'github-credentials', url: 'https://github.com/mr3668323/MERN_STACK_RESTAURANT_RESERVATION.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Simulating build process...'
                // In a real build phase for a MERN app, you might run:
                // - npm install (for backend and frontend)
                // - npm run build (for frontend)
                // - any backend build steps
            }
        }
    }
}
