pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t chakri8991/ecommerce:v1 .'
            }
        }

        stage('Docker Push') {
            steps {
                sh 'docker push chakri8991/ecommerce:v1'
            }
        }
    }
}


