pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("fabricioveronez/api-produto", '-f ./src/Dockerfile ./src') 
                }                
            }
        }
    }
}