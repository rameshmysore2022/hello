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
                sh 'hello_world.sh'
            }
        }
        stage('Deploy') {
            steps {
                sh 'hello_world.sh'
            }
        }
    }
}
