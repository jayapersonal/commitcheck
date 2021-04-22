  pipeline {

agent any
    def result = "haii"
    stages {

        stage ('commit pattern check') {
            steps {
                script {
                echo ${result}
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
