pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('MidLevel') {
            steps {
                echo 'MidLevel.'
                error 'Error Occurred'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye.'
            }
        }
    }
}
