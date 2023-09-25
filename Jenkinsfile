{
  agent any
  tools{
    maven 'maven'
  }
  stages{
    stage('git clone'){
      steps {
        git 'https://github.com/Anitavb11/Samplepro.git'
      }
    }
    stage('compile'){
      steps{
        sh 'mvn compile'
      }
    }
    stage('test'){
      steps{
        sh 'mvn test'
      }
    }
  }
}
