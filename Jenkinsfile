pipeline {
    agent { docker 'maven:3.5-jdk-8-alpine' }
    stages {
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}