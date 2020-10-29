node {
        stage('Checkout scm') {
               checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], 
                userRemoteConfigs: [[credentialsId:'GItHub',url: 'https://github.com/IndrasenaKallam/Capstone1.git']]])
            }
        
    }
