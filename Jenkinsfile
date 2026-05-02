pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/njokadeclan/NEWAPP.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}