#!groovy
node('master'){
	stage ('Checkout'){
	checkout scm
	sh "git rev-parse --short HEAD > .git/commit-id"
	sh "echo .git/commit-id"
	}
}
