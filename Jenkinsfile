pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                // Clone the repository
                git 'https://github.com/isukataruka12/dummy-portfolio.git'
            }
        }

        stage('Build') {
            steps {
                // No build needed for a simple HTML/CSS project, but you can add steps if necessary
                echo 'Building Project'
            }
        }

        stage('Deploy') {
            steps {
                // You can deploy your files to a server or host them (if you use any)
                echo 'Deploying Project'
            }
        }
    }
}
