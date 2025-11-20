pipeline{
    agent{
        label 'slave-1'
    }
    steps{
        stage('first build'){
            steps{
                echo "hii"
            }
        }
        stage('groovy'){
            steps{
                script{
                    def course == "k8s"
                    if (course == "k8s")
                    println("thanks!!")
                    else
                    println("do enroll")
                }
            }
        }
    }
} 
