pipeline {
    agent any
     tools {
        maven 'Maven 3.6.3'
        jdk 'JDK8'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the pipeline'
                //sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Building the pipeline'
                sh 'mvn test'
            }
            /*post {
                always {
                    junit 'target/surefire-reports/*.xml'
                }
            }*/
        }
        stage('Deliver') {
            steps {
                echo 'Building the pipeline'

            }
        }
    }
}
