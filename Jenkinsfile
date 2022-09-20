pipeline {
    agent any
    stages {
        stage('ECR') {
            steps {
            sh "aws cloudformation create-stack --stack-name takehome-ecr --template-body file://takehome-ecr.yaml --region 'us-east-1'"
            }
        }
    }
}
