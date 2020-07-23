node {  
    stage('SCM') { 
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'Github', url: 'https://github.com/cherukurisai451/maven_demo.git']]])
    }
    stage('BUILD') { 
        sh label: '', script: 'mvn clean package'
    }
    stage('TEST') { 
        // 
    }
}
