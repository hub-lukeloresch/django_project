#!groovy
node('master'){
	stage ('Checkout'){
	checkout scm
	
	sh "git rev-parse --short HEAD > .git/commit-id"
	sh "cat .git/commit-id"
	}
}
