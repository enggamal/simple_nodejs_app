
pipeline {
    agent { label 'ec2' }
    stages {
        
        
        stage('Stage 1') {
            steps {
                sh ''' 
                   docker build -t gamal .
                   docker run -dp 5050:3000 gamal 
                '''
            }
        }
        
    }
}
