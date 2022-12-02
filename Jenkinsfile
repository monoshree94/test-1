pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                docker run --name mynginx1 -p 80:80 -d nginx
                docker ps -a
                }
            }
        }
    }
}
