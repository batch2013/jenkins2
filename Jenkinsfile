pipeline {
        agent any
        stages {
                stage("Build") {
                        steps {
				sh 'mvn -B -Dskiptests clean install' 
                        }
                }
        }
}
