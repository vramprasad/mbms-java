pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps {
                echo 'Checkout stage MS 123'
            }
        }
        stage("Build") {
            steps {
                echo 'Build stage'
            }
        }
        stage("Test") {
             steps {
                 echo 'Test stage'
             }
        }
        stage("Deploy") {
              steps {
                  echo 'Deploy stage'
              }
        }
    }

    post {
        always {
            echo "Always executed"
        }

        success {
            echo "Build is super awesome success"
        }

        failure {
            echo "On no....."
        }
    }

}