pipeline {
    environment {
    registry = "prhomhyse/devops-capstone"
    registryCredential = 'docker-hub'
    }
    
    agent any
    stages {
        stage ('Cloning Git') {
            steps {
                sh 'git clone https://github.com/IndrasenaKallam/Capstone1.git'
            }
        }
     }
}
