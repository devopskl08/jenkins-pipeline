pipeline{
    agent{
        label 'slave-1'
    }
    parameters{
        string(
            name: 'PERSON',
            defaultValue: 'likhitha',
            description: 'whats your name'
        )
    }
    stages{
        stage('parameterstage'){
            steps{
                echo "hello, ${params.PERSON}"
            }
        }
    }
}
