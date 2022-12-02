pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                 docker build -t nginx .
                } 
            }
        }
    }
}
