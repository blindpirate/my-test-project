pipeline {
    agent any
    stages {
        stage('Unit test') {
            steps {
                echo 'Test my project'

                sh './mvnw verify'
            }
        }
    }
}
