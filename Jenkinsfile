pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Hello2') {
            steps {
                bat 'node index.js'
        }
    }
}
}
