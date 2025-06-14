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
                bat 'npm start'
                bat 'timeout /t 5'
            }
        }

        stage("Tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}