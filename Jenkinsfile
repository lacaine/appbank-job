pipeline{
    agent any
    stages{
        stage(1'disk-free-space'){
            steps{
                sh 'df -h'
            }
        }
        stage(2'disk-block'){
            steps{
                sh 'lsblk'
            }
        }
    }
}