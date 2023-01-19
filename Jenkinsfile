pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                 script{
                
                 zip yoa-V$-{BUILD_NUMBER}.zip *-x Jenkinsfile
               }
            }
        }
    }
}