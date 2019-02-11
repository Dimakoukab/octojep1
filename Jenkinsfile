pipeline {
    agent none
    stages {
        stage('Stage 1') {
            agent {node {label 'bzi'}}
            steps {
                echo 'Hola from Staitama! '
            }
        stage('Stage 2') {
            agent { node {label 'wakarimashta'}}
            steps {
                echo 'Hola from Naruto !'
            }
        }
    }
}
