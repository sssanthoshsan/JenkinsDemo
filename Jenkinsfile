pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build') {
            steps {
                build 'BashBuild'
                echo 'in build'
            }
        }
        stage('Test') {
            steps {
                echo 'in test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'in deploy'
            }
        }
    }
}
