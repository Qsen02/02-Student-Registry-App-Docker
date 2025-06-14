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
                bat 'start /b npm start'
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