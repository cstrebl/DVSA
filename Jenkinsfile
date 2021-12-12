pipeline {
  agent any
  stages {
    stage('Check Source Code') {
      steps {
        sh '''#!/bin/bash
../../bin/shiftleft.cli  -t 36000 code-scan  -s .  -nb'''
      }
    }

  }
}