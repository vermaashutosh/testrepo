node {
	env.PATH = "C:\Maven3/bin:${env.PATH}"
	
	stage 'Build'

	checkout scm
	bat 'mvn clean package'
}
