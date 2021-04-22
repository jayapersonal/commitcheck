pipeline { 
  agent any 
  stages {
    stage('test stage'){
      steps {
        sh """#!/bin/bash
            myvar=somevalue
            echo "The value is \$myvar"
        """
      }
    }
  }
}
