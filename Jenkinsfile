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
        choice(
            name: 'CHOICE',
            choices: ['one','two','three'],
            description: 'piick some number  from below'
        )
        booleanParam(
            name: 'TOOGLE',
            defaultValue: true,
            description: 'toogle the value'
        )
        text(
            name: 'RELEASEDETAILS',
            defaultValue: '',
            description: 'enter some details about todays release'
        )
    }
    stages{
        stage('parameterstage'){
            steps{
                echo "hello, ${params.PERSON}"
                echo "Release notes, ${params.RELEASEDETAILS}"
            }
        }
    }
}
