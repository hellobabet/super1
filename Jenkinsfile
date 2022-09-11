

pipeline {
    agent any

    stages {
        stage('pagal checkout'){ git branch: 'main', url: 'https://github.com/hellobabet/super1.git'}
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
