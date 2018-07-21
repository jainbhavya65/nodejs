pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
              docker build -t jainbhavya65/test:v1 .
              docker push jainbhavya65/test:v1
            }
        }
    }
}
