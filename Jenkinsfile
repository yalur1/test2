pipeline {
    agent any
    parameters {
        string(Name2: 'PERSON', defaultValue: 'trilok', description: 'Who should I say hello to?')
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "echo $Name >> data.txt"
                echo "echo $Name2"
                echo "cat ./data.txt"
            }
        }
    }
}
