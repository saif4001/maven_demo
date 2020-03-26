node {
    stage('SCM checkout'){
    git credentialsId: 'Github', url: 'https://github.com/cherukurisai451/maven_demo.git'
}
    stage('Build'){
        bat label: '', script: 'mvn clean package'
    }
}
