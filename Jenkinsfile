pipeline {
    agent any
    stages {
        agent { docker { label 'docker' } }
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
