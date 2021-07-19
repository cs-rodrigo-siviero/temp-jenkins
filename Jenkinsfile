pipeline {
    agent any
    stages {
        stage('build') {
            agent { docker { label 'docker' } }
            steps {
                sh 'php --version'
            }
        }
    }
}
