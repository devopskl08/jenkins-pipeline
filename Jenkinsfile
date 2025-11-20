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
        stage('stageenv'){
            steps{
                echo "stage env"
            }
        }
        stage ('prodenv'){
            steps{
                timeout (time: 5 , unit: 'SECONDS' ){
                    echo "execote pprod env"
                }
            }
        }
    }
}
