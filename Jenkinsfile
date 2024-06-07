pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build '2ndfreestylejob'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying!!!!'
            }
        }
    }
}
