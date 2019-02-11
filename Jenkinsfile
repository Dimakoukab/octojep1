pipeline
{
    agent none
    stages
    {
        stage('Stage 1') {
            agent { node { label 'bzi' }}
            steps {
                echo 'Hola from Staitama!'
                sh 'pwd;ls -ltr'
            }
        }

        stage('Stage 2') {
            agent { node { label 'wakarimashta'} }
            steps {
                echo 'Hola from Naruto !!'
            }
        }
    }
}
