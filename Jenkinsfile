pipeline {
    agent any

    environment {
   
        DOCKERHUB_CREDS = credentials('dockerhub-creds')
        IMAGE_NAME = "arrreeb/react-trend-app"
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t $IMAGE_NAME:latest .'
            }
        }

        stage('Push to DockerHub') {
            steps {
                sh 'echo $DOCKERHUB_CREDS_PSW | docker login -u $DOCKERHUB_CREDS_USR --password-stdin'
                sh 'docker push $IMAGE_NAME:latest'
            }
        }

        stage('Deploy to EKS') {
            steps {
                
                sh 'kubectl apply -f k8s-deploy.yaml'
            }
        }
    }
}
