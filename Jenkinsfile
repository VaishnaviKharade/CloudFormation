pipeline{
    agent any
    stages {
        stage('submit stack') {
            steps {
                sh "aws cloudformation create-stack --stack-name Vaishnavi --template-body file://ec2.yaml --region ap-south-1"
            }
        }

    }
}
