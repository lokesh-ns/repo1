pipeline{
    agent any

    stages{

        stage ('stage 1'){
            steps{
                sh 'echo "hey there" >> myfile.txt'
            }
        }

        stage('stage 2'){
            steps{
                sh 'echo "hey this is stage 2"'
                sh 'pg myfile.txt'
            }
        }

        stage('stage 3'){
            steps{
                sh 'echo "hey this is stage 3"'
            }
        }
    }
}