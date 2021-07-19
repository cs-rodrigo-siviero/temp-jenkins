pipeline {
    agent {
        docker {
            label 'docker'
            image 'php:latest'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
    }
}
