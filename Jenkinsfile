pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                bat 'pwd'
                bat 'echo "hey there" >> myfile.txt'
                bat 'ls'
            }
        }

        stage('stage 2'){
            steps{
                bat 'cat myfile.txt'
                bat 'echo "hey this is stage 2"'
            }
        }

        stage('stage 3'){
            steps{
                bat 'echo "hey this is stage 3"'
            }
        }
    }
}