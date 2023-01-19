pipeline {
    agent any

    stages {
        
        stage('create a zip file') {
            steps {
            zip yao-V-${BUILD_NUMBER}.zip* -x jenkinsfile README.md
            }
        }
        
        
    }
}
