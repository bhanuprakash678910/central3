node () {
  stage("download"){
      git 'https://github.com/bhanuprakash678910/mavenproj.git'
  }
  stage("Build"){
      sh '''
      mvn packagee
      '''
  }
}
