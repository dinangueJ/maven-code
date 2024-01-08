pipeline {
    agent any
     tools{
      maven'M2_HOME'
    }
    stage(compile){
      steps{
        sh 'mvn compile'
      }
    }
    stage('install'){
      steps{
        sh 'mvn install'
        sh 'mvn package'

      }
    }
    }

}
