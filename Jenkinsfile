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
                bat 'whoami'
            }
        }
        stage('game') {
            steps {
                echo 'let us play a game'
                bat 'python --version'
            }
        }
    }
}
