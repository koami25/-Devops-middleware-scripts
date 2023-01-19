pipeline {
    agent any

    stages {
        
        stage('create zip file ') {
            steps {
                 
                
               sh  'zip yawa-V-${BUILD_NUMBER}.zip * -x Jenkinsfile README.md'
               
            }
        }
    }
}