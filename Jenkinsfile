pipeline {
	agent any
    stages {
	    stage('clean build'){
          steps {
                sh './gradlew -b build.gradle clean build'
            }
	    }
    }
}
