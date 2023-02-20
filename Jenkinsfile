pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                sh 'echo "hey there" >> file2.txt'
            }
        }

        stage('stage 2'){
            steps{
                sh 'cat file2.txt'
                echo "hey this is stage 2"
            }
        }

        stage('stage 3'){
            steps{
                echo "hey this is stage 3"
            }
        }
    }
}