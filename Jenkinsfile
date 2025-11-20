pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('first build'){
            steps{
                echo "hii"
                sleep 20
                echo "sleep done"
                
            }
        }
        stage('groovy'){
            steps{
                script{
                    def course = "k8s"
                    if (course == "k8s")
                    println("thanks!!")
                    else
                    println("do enroll")
                }
            }
        }
    }
}
