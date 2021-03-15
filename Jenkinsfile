pipeline {
  agent { label 'slave1' }              
stages{
      stage('deploy to S3'){
          steps{
              sh 'aws s3 cp index.html s3://anushka0112.com/index.html'
              sh 'aws s3 cp error.html s3://anushka0112.com/error.html'
             
          }
      }
  }
}
