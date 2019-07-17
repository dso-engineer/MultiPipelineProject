pipeline {
    agent any

    stages {
        stage('Checkout RAVE') {
            steps {
                echo 'Checkout from version control'
            }
        }
        stage('Start Build Notification') {
            steps {
                echo 'Send Slack Message'
            }
        }
        stage('Compile RAVE') {
            steps {
                echo 'Run a Windows Batch Script'
            }
        }
        stage('Archive') {
            steps {
                echo 'Checks if running on a Unix-like node'
            }
        }
        stage('Post Build Notification') {
            steps {
                echo 'Send Slack Message'
            }
        }
        stage('Last stage') {
            steps {
                echo 'last part'
            }
        }
    }
}
