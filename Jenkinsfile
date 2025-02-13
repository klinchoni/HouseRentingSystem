pipeline {
    agent any
    stages {
        stage('Build Project') {
            steps {
                bat 'dotnet build'
            }
        }
         stage('Run dotnet tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}