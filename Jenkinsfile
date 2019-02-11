pipeline {
    agent none
    stages {
        stage('Stage 1') {
            agent {label 'bzi'}
            steps {
                echo 'Hello world!'
            }
        stage('Stage 2') {
            agent {label 'zbi'}
            steps {
                echo 'Hello hola!'
            }
        }
    }
}
