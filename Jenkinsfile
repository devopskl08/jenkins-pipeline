pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('Build'){
            steps{
            echo "building Application"
            }
        }
        stage('codeAnalysis'){
            steps{
            echo "scanning the code"
            }
        }
        stage('dockerbuildpush'){
            steps{
            echo "build and push docker images"
            }
        }
        stage('deply to dev'){
            steps{
            echo "deploying to dev application"
            }
        }
        stage('deply to test'){
            steps{
            echo "deploying to test application"
            }
        }
        stage('deply to stage'){
            steps{
            echo "deploying to stage application"
            }
        }
        stage('deply to prod'){
            options{
                timeout (time: 300, unit: 'SECONDS')
            }
            input{
                message "doing prod deployment?"
                ok 'yes'
                submitter 'likhitha,fhani,raghuSRE'
            }
            steps{
            echo "deploying to prod application"
            }
        }
    }

}
