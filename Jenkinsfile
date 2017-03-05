#!groovy
node('master'){
	stage ('Checkout') {
		checkout scm
		sh "git rev-parse --short HEAD > .git/commit-id"
	}
	stage ('Build Image') {
		echo 'build'
		sh "cat .git/commit-id"
	}

}
