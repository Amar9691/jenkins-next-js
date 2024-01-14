pipeline{
    agent any
    stages{
        stage('development'){
            steps{
                sh 'echo "Start from tomorrow"'
            }
        }
        stage('testing'){
            steps{
                sh 'node -v'
            }
        }
        stage('production'){
            steps{
                sh 'node -v'
            }
        }
    }
}