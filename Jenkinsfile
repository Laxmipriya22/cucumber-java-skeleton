pipeline {
	agent any
    stages {
	    stage('clean Test'){
          steps {
               // sh './gradlew -b build.gradle clean test'
		 sh './gradlew -Dcucumber.options="classpath:skeleton/belly.feature:4 --plugin pretty"'

            }
	    }
    }
}
