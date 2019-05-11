pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'g++ sample.cpp -o sample'
                echo 'Hello'
            }
        }
        stage('Run') {
            steps {
                sh './sample'
            }
        }
    }
}