pipeline {
    agent none 
  
        stage('Example Test') {
            agent { docker 'openjdk:8-jre' } 
            steps {
                echo 'kkkkkddo, JDK'
                sh 'java -version'
            }
        }
    }
}