pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
 withMaven(jdk: 'JAVA_HOME', maven: 'Maven3') {
        sh 'mvm clean install'
}
    }
  }

}
}
