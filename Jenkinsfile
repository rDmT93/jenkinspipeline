pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                echo 'eferferfe'
            }
            post {
                success {
                    echo 'Now Archiving...'
                    archiveArtifacts artifacts: '**/target/*.war'
                }
            }
        }
    }
}