pipeline {
    agent any
    stages {
        stage ('Build'){

            steps{
                echo "Etapa build no Disponible"
            }
        }

        stage('Test'){
            steps{
                echo "Estapa Test no Disponible"
            }
        }
        stage('Deploy'){
            steps{
                sh "docker-compoust down -v"
                sh "docker-compoust up -d --build"
            }
        }
    }
}