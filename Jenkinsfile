pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

pipeline {
    agent { docker { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
