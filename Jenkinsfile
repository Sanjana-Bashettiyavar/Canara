pipeline{
  agent any
  stages{
    stage('printing info'){
      steps{
        sh """ ${env.JOB_NAME}
        echo ${env.BUILD_ID}
        uptime
        pwd
        whoami
        hostname
        """
      
       
      }
    }
  }
}
        
