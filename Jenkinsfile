pipeline {
    agent any

    stages {
        stage('Checkout App Code') {
            steps {
                git url: 'https://github.com/Neetinkumar/python', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo "Build triggered from GitHub push!"
                sh 'ls -la'
            }
        }
    }
}
