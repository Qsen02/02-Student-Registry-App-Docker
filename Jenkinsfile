pipeline {
    agent any

    stages{
        stage("Build"){
            steps {
                sh 'npm i'
            }
        }

        stage("Tests"){
            steps{
                sh 'npm test'
            }
        }
    }
}