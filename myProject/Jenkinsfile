node {
  stage('SCM Checkout') {
    git 'https://github.com/kyhwang0/testArea'
  }
  stage('Compile-Package') {
    sh 'mvn package'
  }
}
