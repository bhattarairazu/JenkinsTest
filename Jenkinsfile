pipeline{
    agent any
    stages{
    stage('build'){
        steps{
      
            sh "mvn clean"
            
        }        
    }
    stage('Test'){
        steps{
            sh "mvn test"
        }
    }
    stage('Deploy'){
        steps{
            sh "mvn package"
        }
    }
    }
}
