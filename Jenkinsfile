pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'trilok', description: 'Who should I say hello to?')
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "echo $Name >> data.txt"
                echo "echo ${params.PERSON}"
                echo "cat ./data.txt"
            }
        }
    }
}
