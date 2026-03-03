pipeline{
  agent any

  stages{
    stage('Clone'){
      steps{
        git url:'https://github.com/AnjaneyK97/simple_jenkins_demo.git',
          branch:'main'
      }
    }
    stage('Run Script'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
