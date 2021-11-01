pipeline{
   agent any
    stages{
        stage("one"){
            steps{
              echo "hello"
            }
        }
        stage("two"){
        steps{
            echo "world"
        }
        }
    }
    post{
        always{
            echo "qwertyuiop"
        }
    }

}