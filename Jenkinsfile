node{
	stage('SCM Checkout'){
		git 'https://github.com/rhlsvn/echo-hello'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
