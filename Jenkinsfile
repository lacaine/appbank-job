pipeline{
    agent any
    stages{
        stage('1-diskfreespace'){
            steps{
                sh 'df -h'
            }
        }
        stage('2-diskblock'){
            steps{
                sh 'lsblk'
            }
        }
        stage('3-memorycheck'){
            steps{
                sh 'free -g'
            }
        }
    }
}