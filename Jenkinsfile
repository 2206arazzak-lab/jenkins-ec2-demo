

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building my first Jenkins project!'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                sh 'test -f index.html'
                echo 'Test passed: index.html exists'
            }
        }
    }
}
