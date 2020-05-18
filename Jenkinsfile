pipeline {
    agent any
    stages {
        stage("git"){
        steps{
            git credentialsId: 'GITHUB_CRED', url: 'https://github.com/cherukurisai451/maven_demo.git'
        }
}

        stage("BUILD"){
            steps {
                sh label: '', script: 'mvn clean package'
            }
    }
}
}
