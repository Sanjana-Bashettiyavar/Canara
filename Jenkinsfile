pipeline{
  agent any
  stages{
    stage('printing info'){
      steps{
        sh """ 
        uptime
        pwd
        whoami
        hostname
        echo "$JOB_NAME"
        echo "$BUILD_ID"
        """
      }
    }
  }
}
        
