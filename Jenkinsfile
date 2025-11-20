pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('firststage'){
            steps{
                retry(3)
                echo "welcome"
                error "failed"
            }
            echo "After 3 trials not worked"
        }
        stage('second scans'){
        steps{
            echo "normal"
        }}
    }
}
