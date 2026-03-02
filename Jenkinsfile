node {
  stage('cloning maven project')
  {
    git 'https://github.com/Sumukha47/mavenproject.git'
  }
  stage('Building maven project')
  {
    sh 'mvn package'
  }
}
