pipeline {
    agent any
    tools {
        maven 'MAVEN_3.8.8'
    }
    stages {
        stage ('Build') {
            echo 
            sh 'mvn --version'
        }
    }
    stage ('open jdk parts') {
        tools {
            jdk 'JDK_17'
            steps {
                echo "this is the jdk version"
                sh 'mvn --version'
            }
        }
    }
}

