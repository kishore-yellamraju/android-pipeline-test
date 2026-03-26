pipeline{
  agent{
    any
  }
  stages {
    stage('build') {
    echo 'cloning reprositery'
    }
    stage('Buils debug apk') {
    echo 'generating apk'
    sh './gradlew assembleDebug'
    }
}
}