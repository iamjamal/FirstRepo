pipeline {
        agent any
        stage("Checkout"){

            checkout scm
        }

        stage("Build"){
            echo "building something"
            // sh './build.sh'

        }

        stage("Run Unit|Integration Tests"){
            echo "running tests"
            }

        }


        stage("Publish to S3"){

            echo "publishing output of build to AWS s3 bucket"

        }

  post {
    success {
      echo "I was successful" 
      }
    failure {
       echo "I failed"
    }
}
