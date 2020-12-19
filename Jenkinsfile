pipeline {
    agent any
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
                //sh 'mvn test'
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
