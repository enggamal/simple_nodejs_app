
pipeline {
    agent { label 'ec2' }
    stages {
        
        
        stage('Stage 1') {
            steps {
                sh ''' 
                   docker build -t gamal .
                   docker run -dp 3000:3000 gamal 
                '''
            }
        }
        
    }
}
