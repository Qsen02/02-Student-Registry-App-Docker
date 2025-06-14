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
                bat 'npm start &'
            }
        }

        stage("Tests"){
            steps{
                bat 'npm test'
            }
        }
    }
}