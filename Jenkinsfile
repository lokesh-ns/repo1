pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                sudo sh 'pwd'
                sudo sh 'echo "hey there" >> myfile.txt'
                sudo sh 'ls'
            }
        }

        stage('stage 2'){
            steps{
                sudo sh 'cat myfile.txt'
                sudo sh 'echo "hey this is stage 2"'
            }
        }

        stage('stage 3'){
            steps{
                sudo sh 'echo "hey this is stage 3"'
            }
        }
    }
}