pipeline {
    agent {label 'foreman'}
    stages {
        stage('Create a file') {
            steps {
                sh 'cd /home/jenkins && touch hello-world'
            }
        }
      
    }
}
