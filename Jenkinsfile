pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3testookbucket --template-body file://s3cft.json --region 'us-gov-west-1'"
              }
             }
            }
            }
