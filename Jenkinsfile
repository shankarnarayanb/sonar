pipeline {
    agent any
    stages {
        stage ('Mvn') {
            steps {
               sh "mvn --version"
            }
        }
       stage ('Mvn install') {
            steps {
               sh "mvn install"
            }
        }
    }
}
