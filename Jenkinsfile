pipeline{
    agent{
        label 'AGENT-1'
    }
    options {
                // Timeout counter starts BEFORE agent is allocated
                timeout(time: 30, unit: 'MINUTES')
                disableConcurrentBuilds()
            }
    stages{
        stage('Build'){
            steps{
                sh 'echo this is Build'
            }
               
        }
        stage('Test'){
            steps{
                sh 'echo this is Tes'
                sh 'sleep 10'
            }
        }
        stage('Deploy'){
            steps{
                sh 'echo this is Deploy'
            }
        }
    }
    
}