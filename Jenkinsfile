pipeline {
    agent any
    
    stages {
        stage('Print PR Number') {
            steps {
                script {
                   sh 'git clone https://github.com/vignesh-s19/improved-octo-engine.git'
                    def prNumber = env.CHANGE_ID // Jenkins environment variable for PR number
                    echo "PR Number: ${prNumber}"
                }
            }
        }
    }
}
