#!groovy
node('master'){

		try{
		stage ('Checkout'){
		checkout scm
		sh "git rev-parse --short HEAD > .git/commit-id"
		}
		echo .git/commit-id
		}
}
