pipeline {
    agent any
    
    stages {
        stage('Print PR Number') {
            steps {
                script {
                    def prNumber = env.CHANGE_ID // Jenkins environment variable for PR number
                    echo "PR Number: ${prNumber}"
                }
            }
        }
    }
}
