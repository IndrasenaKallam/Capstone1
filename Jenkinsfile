node {
        stage('Checkout scm') {
               parallel checkout:checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], 
                userRemoteConfigs: [[url: 'https://github.com/IndrasenaKallam/Capstone1.git']]])
            }
        
    }
