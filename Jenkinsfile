  pipeline {
          options {
        ansiColor('xterm')
        timeout(time: 60, unit: 'MINUTES')
        disableConcurrentBuilds()
        buildDiscarder(logRotator(numToKeepStr: '30'))
    }
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