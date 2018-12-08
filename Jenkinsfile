pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh ''' mkdir -p /var/tmp/raju '''
            }
        }
        stage('Test') { 
            steps {
                 sh ''' df -h '''
            }
        }
        stage('Deploy') { 
            steps {
                sh ''' rm -rf /var/tmp/raju '''
            }
        }
    }
}
