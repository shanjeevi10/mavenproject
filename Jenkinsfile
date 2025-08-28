 
pipeline {
    agent any
    stages {
        stage('buld'){
            steps{
                echo"Hello build stage"
                sh 'hostname'
            }
        }
        stage('test'){
            steps{
                echo"Hello test stage"
                sh 'pwd'
            }
        }
        stage('deploy'){
            steps{
                echo "Hello deploy stage"
                sh 'java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App'
            }
        }    
    }
}    
