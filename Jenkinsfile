pipeline {
  agent any
  stages {
  stage('maven install') {
    steps {
 withMaven(globalMavenSettingsConfig: 'null', jdk: 'JAVA_HOME', maven: 'Maven3', mavenSettingsConfig: 'null') {
        sh 'mvm clean install'
}
    }
  }

}
}
