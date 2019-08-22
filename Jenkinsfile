pipeline {
	agent any
    stages {
	    stage('clean Test'){
          steps {
                sh './gradlew -b build.gradle clean test'
            }
	    }
    }
}
