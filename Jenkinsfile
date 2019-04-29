// Powered by Infostretch 

timestamps {

node () {

	stage ('terraformTest - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '32fe91a9-27de-465a-8c0b-40b2441209c4', url: 'https://github.com/pazhanivelm/terraformTest.git']]]) 
	}
	stage ('terraformTest - Build') {
 	
withEnv(["JAVA_HOME=${ tool '"+JDK+"' }", "PATH=${env.JAVA_HOME}/bin"]) { 
		// Shell build step
sh """ 
echo "wow" 
 """ 
	}
}
}
}