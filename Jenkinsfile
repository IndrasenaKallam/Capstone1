node {
        enivronment {
                JOB_NAME = 'Test'
                BUILD_NUMBER = 2
                BUILD_URL = 'None'   
                
        }
        stage('Checkout scm') {
               checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], 
                userRemoteConfigs: [[credentialsId:'GItHub',url: 'https://github.com/IndrasenaKallam/Capstone1.git']]])
        }
        post {
        always {
            emailext body: 'A Test EMail', recipientProviders: [['senadevops@gmail.com'], [$class: 'RequesterRecipientProvider']], subject: 'Test'
        }
        
        
    }
