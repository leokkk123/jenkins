//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'maven:3.9.2' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
