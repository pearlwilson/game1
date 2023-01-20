pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('game') {
            steps {
                echo 'let us play a game'
                sh 'python guessnumber.py'
            }
        }
    }
}
