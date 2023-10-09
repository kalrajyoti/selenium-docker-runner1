pipeline{

    agent any

    stages{

        stage('Run Test'){
            steps{
                sh "docker-compose up"
            }
        }

        stage('Bring Grid down Test'){
            steps{
                sh "docker-compose down"
            }
        }

    }
}