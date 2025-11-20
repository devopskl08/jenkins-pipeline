pipeline{
  agent {
    label 'slave-1'
  }
    stages{
      stage('hostname'){
            steps{
               sh 'hostname -i'
             }
       }
      stage('new stage'){
        steps{
        echo "hello"}
            }
} 
