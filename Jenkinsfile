pipeline{
    agent{
        label 'AGENT-1'
    }
    options {
                // Timeout counter starts BEFORE agent is allocated
                timeout(time: 1, unit: 'SECONDS')
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
            }
        }
        stage('Deploy'){
            steps{
                sh 'echo this is Deploy'
            }
        }
    }
    
}