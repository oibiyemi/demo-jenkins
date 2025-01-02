pipeline {
    agent any
   

    environment{
        DEMO='demo-jenkins'
    }

    stages {
        stage('Hello') {
            steps {
                echo "This is the build number: ${env.BUILD_NUMBER}"
            }
        }
        stage('List env') {
           steps {
               echo 'Listing default environmental variables'
               sh 'env'
           }
        }
    }
} 


