pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo $Name >> data.txt
            }
        }
    }
}
