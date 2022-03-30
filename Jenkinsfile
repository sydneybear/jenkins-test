node{
  stage('SCM Checkout') {
    git 'https://github.com/sydneybear/jenkins-test'
  }
  stage('Compile-Package) {
    sh 'mvn package'
  }
}
