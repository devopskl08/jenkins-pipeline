pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('test'){
            steps{
                  echo "test env"
            }
        }
        stage('dev'){
            steps{
                echo "dev env"
            }
        }
        stage(stage env){
            steps{
                echo "stage env"
            }
        }
        stage (prod env){
            steps{
                timeout (time: 5 , units: 'SECONDS' ){
                    echo "execote pprod env"
                }
            }
        }
    }
}
