pipeline {
    agent any

  tools {nodejs "node"}

    stages {
        // stage('Git') {
        //     steps {
        //         git 'https://github.com/Lucas-knut/app-expressjs'
        //     }
        // }
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