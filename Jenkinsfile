pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                zip yao-v${BUILD_NUMBER}.zip * --exclude jenkinsfile README
            }
        }
    }
}