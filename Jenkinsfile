pipeline {
    agent any
    tools {
        maven "maven1"
    }
    stages {
        stage("compile") {
            steps {
                sh "mvn compile"
            }
        }
        stage("test") {
            steps {
                sh "mvn test"
            }
        }
        stage("Build") {
            steps {
                sh "mvn package"
            }
        }
    }
}
