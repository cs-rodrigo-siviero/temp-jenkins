pipeline {
    agent { docker { label 'docker' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
