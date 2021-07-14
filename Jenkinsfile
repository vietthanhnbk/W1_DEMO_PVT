node('main') {
    stage('scm') {
        checkout([$class: 'GitSCM', 
          branches: [[name: '*/main']], 
          doGenerateSubmoduleConfigurations: false, 
          extensions: [], 
          submoduleCfg: [], 
          userRemoteConfigs: [[credentialsId: 'github_account', 
          url: 'https://github.com/vietthanhnbk/W1_DEMO_PVT.git']]])
    }

    stage('build') {
        echo "Hi"
    }
}