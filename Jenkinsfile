pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello') {
            steps {
                sh 'pip install python'
            }
        }
        stage('game') {
            steps {
                echo 'let us play a game'
                sh 'python --version'
            }
        }
    }
}
