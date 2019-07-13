pipeline {
agent any
stages{
  stage('Build'){
    steps{
    sh '/usr/local/src/maven3/bin/mvn clean install'
    }
  }
  stage('Test'){
    steps{
    sh '/usr/local/src/maven3/bin/mvn test'
    }
  }
}
}
