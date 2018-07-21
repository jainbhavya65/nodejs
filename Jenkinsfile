pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
              sh 'docker build -t jainbhavya65/test:v1 .'
              sh 'docker push jainbhavya65/test:v1'
            }
        }
    }
}
