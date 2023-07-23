pipeline {
  agent any

  stages{
    stage('hello'){
      steps{
        echo "hello"
      }
    }
    stage('hi'){
      steps{
        echo "hi"
        sh 'pwd'
      }
    }
  }
}