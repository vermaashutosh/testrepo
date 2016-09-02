node {
	env.PATH = "${tool 'M3'}/bin:${env.PATH}"
	
	stage 'Build'

	checkout scm
	sh 'mvn clean package'
}
