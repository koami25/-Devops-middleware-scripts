pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                 
                
               sh  'zip yoa-V-${BUILD_NUMBER}.zip *-x Jenkinsfile'
               
            }
        }
    }
}