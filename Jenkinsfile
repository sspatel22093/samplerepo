pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3testbucketsunny --template-body file://S3CFT.json --region 'us-gov-west-1'"
              }
             }
            }
            }
