pipeline {
    agent any

    stages{
        stage("Build"){
            steps {
                sh npm i
            }
        }

        stage("Start app"){
            steps{
                sh npm start
            }
        }

        stage("Tests"){
            steps{
                sh npm test
            }
        }
    }
}