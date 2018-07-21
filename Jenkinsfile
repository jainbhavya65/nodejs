pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
              docker push jainbhavya65/test
            }
        }
    }
}
