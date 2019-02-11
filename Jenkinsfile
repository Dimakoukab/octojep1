pipeline
{
    agent none
    stages
    {
        stage('Stage 1') {
            node { agent { label 'bzi'} }

            steps {
                echo 'Hola from Staitama!'
            }
        }

        stage('Stage 2') {
            node { agent {label 'wakarimashta'} }

            steps {
                echo 'Hola from Naruto !!'
            }
        }
    }
}
