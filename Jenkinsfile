pipeline {
    agent any

    stages{
        stage("Build"){
            steps {
                bat 'npm i'
            }
        }

        stage("Start app"){
            steps{
                bat 'nohup npm start'
            }
        }

        stage("Tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}