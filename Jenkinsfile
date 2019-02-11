pipeline {
    agent none
    stages {
        stage('Stage 1') {
            agent {label 'bzi'}
            steps {
                echo 'Hola from Staitama'
            }
        stage('Stage 2') {
            agent {label 'wakarimashta'}
            steps {
                echo 'Hello from Naruot!'
            }
        }
    }
}
