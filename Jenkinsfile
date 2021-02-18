pipeline {
	agent any
	stages {
		stage('Submit Stack') {
			sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://simplestS3.json --region 'us-east-1'"
		}
	}
}