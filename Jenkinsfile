  pipeline {

agent any
    environment {
   result=""
   }
    stages {

        stage ('commit pattern check') {
            steps {
                script {
                echo result
                }
            }
        }    
    }
        post {
        always {
            cleanWs()
        }
    }
  }
