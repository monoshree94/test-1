pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                docker run --name mynginx1 -p 80:80 -d nginx
                docker ps -a
            }
        }
    }
}
