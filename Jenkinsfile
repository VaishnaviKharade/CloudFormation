pipeline{
    agent any
    stages {
    stage("Checkout scm")
{
    steps{
          checkout scm
}
}
        stage('submit stack') {
            steps {
                //bat "aws cloudformation create-stack --stack-name Vaishnavi --template-body file://ec2.yaml --region ap-south-1"
                bat "aws ec2 describe-instances --region ap-south-1"
            }
        }

    }

}
