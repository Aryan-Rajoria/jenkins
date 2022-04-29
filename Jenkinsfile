pipeline {
    agent { docker { image 'python:3.8-slim' } }
    stages {
        stage('build') {
            steps {
                echo 'Build of lab.py is starting'
                bat 'python lab.py'
                echo 'Done'
            }
        }
        stage('testing'){
            steps{
                echo 'Doing testing'
                bat 'python lab.py'
                echo 'Done'
            }
        }
    }
}