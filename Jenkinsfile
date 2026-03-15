pipeline{
  agent any

  stages{
    stage('clone'){
      steps{
        git url:'https://github.com/AnjaneyaK97/simple_jenkins_demo.git',
          branch:'main'
      }
    }
    stage('Compile Java Program') {
      steps {
        sh 'javac Hello.java'
      }
  }

  stage('Run Java Program') {
    steps {
      sh 'java Hello'
    }
  }
}
}
