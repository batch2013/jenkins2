pipeline {
	agent {
		label 'slave'
	}
        stages {
                stage("Build") {
                        steps {
				sh 'mvn -B -Dskiptests clean install' 
                        }
                }
        }
}
