 
pipeline {
    agent any
    stages {
        stage('buld'){
            steps{
                echo"Hello build stage"
                sh 'mvn compile'
            }
        }
        stage('test'){
            steps{
                echo"Hello test stage"
                sh 'mvn test'
            }
        }
     tage('package'){
            steps{
                echo"Hello package stage"
                sh 'mvn package'
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
