pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                zip middleware-V${BUILD_NUMBER}.zip *-x Jenkinsfile
            }
        }
    }
}