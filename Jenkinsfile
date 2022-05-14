pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://cloudformation-S3-bucket.yml  --region 'eu-west-2'"
              }
             }
            }
            }
