pipeline {
    agent { docker { image 'docker-pawn-compiler' } }
    stages {
        stage('build') {
            steps {
                sh './home/build/pawncc .'
            }
        }
    }
}