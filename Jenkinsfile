pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('firststage'){
            steps{
                retry(3){
                echo "welcome"
                error "failed"
            }}
            echo "3 tries"
        }
        stage('second scans'){
        steps{
            echo "normal"
        }}
    }
}
