pipeline{
    agent{
        label 'slave-1'
    }
    tools{
        maven 'MAVEN_3.8.9'
    }
    stages{
        stage ("maven"){
            steps{
                echo "hello from maven"
                sh "mvn --version"
            }
        }
    }
}
