pipeline {
    agent any
    stages {
        stage('Tests unitaires') {
            steps {
                bat 'mvn clean test -Dtest=MathClass'   // sous Linux : sh '...'
            }
            post {
                always { junit '**/target/surefire-reports/*.xml' }
            }
        }
    }
}
