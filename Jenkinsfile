pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
      withMaven {
  sh 'mvm clean install'
}
    }
  }

}
}
