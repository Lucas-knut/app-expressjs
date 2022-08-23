pipeline {
    agent any

  tools {nodejs "node"}

    stages {
        stage('Git') {
            steps {
                git branch: 'master',
                credentialsId: 'bf6ac58f-85c2-4f82-aa8e-4b4e2ae81901',
                url: 'ssh://git@github.com:Lucas-knut/app-expressjs.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm config ls'
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deboy'
            }
        }
    }
}