pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
        git url :'https://github.com/chethan6186/j-d.git'
      }
    }
    stage('Run Script'){
      steps{
        sh'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
