pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                bash 'pwd'
                bash 'echo "hey there" >> myfile.txt'
                bash 'ls'
            }
        }

        stage('stage 2'){
            steps{
                bash 'cat myfile.txt'
                bash 'echo "hey this is stage 2"'
            }
        }

        stage('stage 3'){
            steps{
                bash 'echo "hey this is stage 3"'
            }
        }
    }
}