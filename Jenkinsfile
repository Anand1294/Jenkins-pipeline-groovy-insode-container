pipeline {
    agent {
        docker {image 'groovy:latest'}
    }
    stages {
        stage ('Groovy Version Check') {
            steps {
                sh 'groovysh --version'
            }
        }
    }
}
