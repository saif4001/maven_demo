node {
    stage('SCM checkout'){
    git credentialsId: 'Github', url: 'https://github.com/cherukurisai451/maven_demo.git'
}
    //this is example of webhook
    stage('Build'){
        bat label: '', script: 'mvn clean package'
    }
}
