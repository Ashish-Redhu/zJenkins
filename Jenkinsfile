pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the web application"'
                // Insert commands to build your web application (e.g., npm install, npm run build)
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the web application"'
                // Insert commands to deploy your web application to your server (e.g., scp, rsync)
            }
        }
    }
}
