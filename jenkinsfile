pipeline {
    agent any
    stages {
     stage('---checkout---') {
            steps {
                bat "git clone https://github.com/cherukurisai451/maven_demo.git"
            }
        }
        stage('---clean---') {
            steps {
                bat "mvn clean"
            }
        }
       stage('--test--') {
            steps {
                bat "mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "mvn package"
            }
        }
    }
}
