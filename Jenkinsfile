pipeline {
    agent any
    stages {
        stage('Automate2 EKS') {
            steps {
            sh "aws cloudformation create-stack --stack-name eshani-EKS-node15 --template-body file://automate2-eks.yaml --region 'us-east-1'"
              }
         }


     }
}
