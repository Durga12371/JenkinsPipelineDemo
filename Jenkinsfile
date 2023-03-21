pipeline {
    agent any
    tools{
        maven 'MAVEN'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
