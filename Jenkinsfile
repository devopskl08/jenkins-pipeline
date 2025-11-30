pipeline{
    agent{
        label 'slave-1'
    }
    stages{
        stage('Build'){
            echo "building Application"
        }
        stage('codeAnalysis'){
            echo "scanning the code"
        }
        stage('dockerbuildpush'){
            echo "build and push docker images"
        }
        stage('deply to dev'){
            echo "deploying to dev application"
        }
        stage('deply to test'){
            echo "deploying to test application"
        }
        stage('deply to stage'){
            echo "deploying to stage application"
        }
        stage('deply to prod'){
            echo "deploying to prod application"
        }
    }

}
