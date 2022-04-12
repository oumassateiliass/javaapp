pipeline {
    agent { any { image 'maven:3.8.4-openjdk-11-slim' } }
    stages {
            stage('build'){
        withMaven(maven: 'mvn') {
            sh "mvn clean package"
        }
    }
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
