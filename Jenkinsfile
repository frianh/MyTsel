pipeline {
  agent none
  stages {
    stage('Get APK') {
      steps {
        echo 'get APK 12345678'
        sh 'curl -O "http://10.0.50.215:8081/artifactory/apk-mytelkomsel/com.telkomsel.telkomselcm.3.9.2.apk"'
      }
    }
    stage('Install APK to Device') {
      steps {
        echo 'Install APK to Device'
      }
    }
  }
}