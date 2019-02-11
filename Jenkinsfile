pipeline {
    agent none
    stages {
        stage('Stage 1') {
            node {label 'bzi'}
            steps {
                echo 'Hola from Staitama'
            }
        stage('Stage 2') {
            node {label 'wakarimashta'}
            steps {
                echo 'Hello from Naruot!'
            }
        }
    }
}
