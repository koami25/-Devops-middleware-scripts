pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                 
                
               sh  'zip yawalove-V-${BUILD_NUMBER}.zip * -x Jenkinsfile README.md'
               
            }
        }
    }
}