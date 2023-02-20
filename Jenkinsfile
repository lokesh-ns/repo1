pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                sh 'pwd'
                sh 'echo "hey there" >> myfile.txt'
                sh 'ls'
            }
        }

        stage('stage 2'){
            steps{
                sh 'cat myfile.txt'
                sh 'echo "hey this is stage 2"'
            }
        }

        stage('stage 3'){
            steps{
                sh 'echo "hey this is stage 3"'
            }
        }
    }
}