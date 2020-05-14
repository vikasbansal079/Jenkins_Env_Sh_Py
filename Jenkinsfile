node("CentOS7"){

	stage("Checkout SCM"){
		deleteDir()
		checkout scm
	}
	
	stage("Run Shell Script"){
		env.Var1="Hello"
		env.Var2="Everyone"
		
		sh """
			pwd
			ls -la
			chmod 755 test.sh
			./test.sh
		"""
	}

}