pipeline {
    agent { Dockerfile true}
    stages {
        stage('Example') {
            steps {
                sh ' docker images '
            }
        }
    }
}
