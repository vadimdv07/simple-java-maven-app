pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '/tmp/apache-maven-3.6.3/bin/mvn clean compile'
            }
        }
    }
}
