

pipeline {
    agent any
    options { skipDefaultCheckout() }
    stages {
        stage('pagal checkout'){ steps { git branch: 'main', url: 'https://github.com/hellobabet/super1.git' } }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
