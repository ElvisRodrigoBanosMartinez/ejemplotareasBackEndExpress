pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "========executing Build========"
            }            
        }
        stage("Build"){
            steps{
                echo "========executing Test========"
            }            
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}