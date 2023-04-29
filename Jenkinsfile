// BUILD_TAG_FOR_THIS_BUILD:-jenkins-jenkins-devops-microservices-pipeline-13
// SCRIPTED
// node {
// 	echo "Build"
// 	echo "Test"
// 	echo "Integration Test"
	
// }
//Declerative pipeline
pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo 'THIS IS BUILD STAGE'
            }
        }
        stage('Testing'){
            steps{
                echo 'THIS IS TESTING STAGE '
            }
        }
        stage('Integration Testing'){
            steps{
                echo 'THIS IS INTEGRATION TESTING'
            }
        }
    }
    post{
        always{
            echo 'THIS IS ALWAYS POST'
        }
        success{
           echo 'THIS IS SUCCESS POST WHEN BUILD GET SUCCUSSFULL EXECUTED'
        }
        failure{
            echo 'THIS WILL EXECUTE WHEN BUILD IS NOT RUNNING PROPERLY'
        }
    }
}