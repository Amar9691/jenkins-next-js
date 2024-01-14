pipeline{
    agent any
    tools{
        node any
    }
    stages{
        stage('development'){
            steps{
                sh 'npm run build'
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