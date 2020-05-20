// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('IntegrationTest') {
// 		echo "IntegrationTest"
// 	}
// }

pipeline {
   agent any
   stages {
	   stage("Build"){
		   steps {
           echo "Build testing"

		   }
	   }
	   stage("test"){
		    steps {
           echo "test env testing"

		   }
	   }
	   stage("IntegrationTest"){
		   steps {
           echo "IntegrationTest testing"

		   }
	   }
   }


}