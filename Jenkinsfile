pipeline {
  agent any

  stages {
      stage('Build Artifact') {
            steps {
              sh "mvn clean package"
              archive 'target/*.jar' //so that they can be downloaded later
            }
        }   
    }
}
