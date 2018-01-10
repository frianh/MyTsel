pipeline {
  agent any
  stages {
    stage('Get APK') {
      steps {
        echo 'test 1234'
        sh(script: 'echo "tesst"')
        sh(script: 'curl -O "http://10.0.50.215:8081/artifactory/apk-mytelkomsel/com.telkomsel.telkomselcm.3.9.2.apk"')
        sh(script: "pwd && ls")
      }
    }
    stage('Install APK to Device') {
      steps {
        echo 'Install APK to Device'
      }
    }
  }
}
