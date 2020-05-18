node {
    stage('SCM checkout'){
    git credentialsId: 'Github', url: 'https://github.com/cherukurisai451/maven_demo.git'
}
    //this is example of webhook and jenkins config dgba'dkhasvzsv
    stage('Build'){
        bat label: '', script: 'mvn clean package'
    }
}
