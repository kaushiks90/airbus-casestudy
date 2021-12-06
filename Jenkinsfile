pipeline {
  agent any
  stages {
    stage('') {
      steps {
        dir(path: 'source/calculation-offer-service/CalculationServiceAPISolution')
      }
    }

  }
  environment {
    ECR_ID = 'us-west-2'
    CALCULATION_SERVICE_IMAGE = 'kaushikv2-casestudy-calculation-service'
    ECR_CREDENTIALS = 'credentials(\'ecr-credentials\')'
  }
}