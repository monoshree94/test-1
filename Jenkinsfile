pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                script {
                 docker run -it -p 80:80 --name nginx nginx
                } 
            }
        }
    }
}
