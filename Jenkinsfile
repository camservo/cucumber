pipeline {
    agent {
        docker { image 'ruby:2.5.0-stretch' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
