pipeline {
    agent {
        label 'ubuntu'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('installations') {
            steps {
                bat 'pip install python'
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
