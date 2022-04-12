pipeline {
    agent { any { image 'maven:3.8.4-openjdk-11-slim' } }
     tools {
    maven 'M3'
     }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
