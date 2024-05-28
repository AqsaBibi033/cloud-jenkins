pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Allication build stage...' 
        }
       }
        stage('Test') {
            steps {
                echo 'Allication test stage' 
        }
        }
        stage('Run') {
            steps {
                echo 'Allication run stage'
                sh'gcloud compute zones list'
                echo "This is my IP"
curl -s ifconfig.co
echo "This is my hostname"
hostname -f
             echo 'updated'   
            }
        }
    }
}
