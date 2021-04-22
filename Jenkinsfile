  pipeline {

agent any
    stages {

        stage ('commit pattern check') {
            steps {
                script {
                  sh """
                echo result
                """
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
