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
   //agent any
   agent { docker { image 'maven:3.6.3'} }
   stages {
	   stage("Build"){
		   steps {
			   sh "mvn --version"
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
   post{
    always {
		echo "always run the application"
	}
    success{
		echo "always succes case run"
	}
	failure{
		echo "run in case fail state::"
	}
   }


}