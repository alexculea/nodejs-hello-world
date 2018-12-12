pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                script {
                    node index
                }
            }
        }
    }
}