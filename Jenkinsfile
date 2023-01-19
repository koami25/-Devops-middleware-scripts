pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                zip middlewareV$-{BUILD_NUMBER}.zip *-x Jenkinsfile
            }
        }
    }
}