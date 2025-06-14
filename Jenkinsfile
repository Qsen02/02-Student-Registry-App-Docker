pipeline {
    agent any

    stages{
        stage("Build"){
            steps {
                sh 'npm i'
            }
        }

        stage("Start app"){
            steps{
                sh 'nohup npm start'
            }
        }

        stage("Tests"){
            steps{
                sh 'npm test'
            }
        }
    }
}