pipeline {
  agent any
  stages {
    stage('s3upload') {
      steps {
        s3Upload(bucket: 'cognitive', pathStyleAccessEnabled: true, file: 'line-test_uat-single-code-branch', path: 'uat-artifacts', workingDir: 'D:\\\\Jenkins\\\\workspace\\\\')
      }
    }
  }
}