pipeline {
    agent any

    stages {
        stage('Checkout RAVE') {
            steps {
                echo 'Checkout RAVE'
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
        stage('Clean Up Workspace') {
            steps {
                echo 'Checks if running on a Unix-like node'
                echo 'Delete workspace when build is done'
            }
        }
    }
}
