node {
  stage('SCM Checkout'){
    git 'git@github.com:sammadu/my-app.git'
  }
  stage('Compile-Package') {
   sh 'mvn package' 
  }


}
