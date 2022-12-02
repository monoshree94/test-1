pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                 app = docker.build("nginx")
                } 
            }
        }
    }
}
