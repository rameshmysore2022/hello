pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "building"'
            }
        }
        stage('Test') {
            steps {
                sh 'python hello_world.py'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python hello_world.py'
            }
        }
    }
}
