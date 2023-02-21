pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                bat 'echo "hey there" >> myfile.txt'
            }
        }

        stage('stage 2'){
            steps{
                bat 'echo "hey this is stage 2"'
                bat 'type myfile.txt'
            }
        }

        stage('stage 3'){
            steps{
                bat 'echo "hey this is stage 3"'
            }
        }
    }
}
