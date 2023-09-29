pipeline{
    agent {
        docker {label 'monitoring-1'
                image 'bibinwilson/jenkins-slave:latest'
        }
        }
    stages {
        stage ('Run sample') {
            
            steps {
                sh 'echo "hello world"'
            }
        }
        
    }
}
