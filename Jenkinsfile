pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('installations') {
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
