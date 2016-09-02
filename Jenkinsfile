node {
	env.PATH = "${tool 'M3'}/bin:${env.PATH}"
	
	stage 'Build'

	checkout scm
	bat 'mvn clean package'
}
