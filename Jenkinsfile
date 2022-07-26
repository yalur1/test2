pipeline {
    agent any
    parameters {
      Name2='trolik'
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
