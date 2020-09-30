pipeline{
        agent any
        stages{
          stage('Make Directory'){
            steps{
              sh "chmod +x run.sh"      
              sh "./run.sh"               
            }
          }
        }
}
