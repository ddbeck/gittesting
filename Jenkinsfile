pipeline {
    agent {
        docker { image 'docker/whalesay' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'cowsay boo'
            }
        }
    }
}
