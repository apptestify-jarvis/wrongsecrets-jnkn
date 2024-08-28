pipeline{
  agent any 
  stages{
    stage('Bomanai'){
      steps{
         sh '''pip install --extra-index-url https://test.pypi.org/simple/ boman-cli-uat==14.5
         ~/.local/bin/boman-cli-uat -a run -cicd jenkins -u https://qa.boman.ai'''
      }
    }
  }
}
