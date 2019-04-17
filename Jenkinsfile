pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "echo ok"
            }
        }
    }
    post {
        success {
            echo "Build succeeded."
        }
        unstable {
            echo "Build got unstable."
        }
        failure {
            echo "Build failed."
        }
    }
}
