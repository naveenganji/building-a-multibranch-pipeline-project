pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
