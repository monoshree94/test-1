pipeline {
    agent { dockerfile true}
    stages {
        stage('Example') {
            steps {
                sh ' docker images '
            }
        }
    }
}
