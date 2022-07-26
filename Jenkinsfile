pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "echo $Name >> data.txt"
                "cat ./data/txt"
            }
        }
    }
}
