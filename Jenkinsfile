pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        dir(path: 'source/calculation-offer-service/CalculationServiceAPISolution') {
          sh 'sh \'pwd\''
        }

      }
    }

  }
  environment {
    ECR_ID = 'us-west-2'
    CALCULATION_SERVICE_IMAGE = 'kaushikv2-casestudy-calculation-service'
    ECR_CREDENTIALS = 'credentials(\'ecr-credentials\')'
  }
}