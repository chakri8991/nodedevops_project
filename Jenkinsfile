pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo "Code checked out from Git"
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Basic Test') {
            steps {
                sh 'node -v'
            }
        }
    }
}

