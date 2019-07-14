pipeline {
agent any
stages{
  stage('Build'){
    steps{
    echo 'The first step in first stage'
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
