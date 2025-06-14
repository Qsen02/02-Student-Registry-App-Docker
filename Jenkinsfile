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
                bat 'start "" node index.js'
            }
        }

        stage("Tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}