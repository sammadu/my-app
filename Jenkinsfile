node {
  stage('SCM Checkout'){
    git 'https://github.com/sammadu/my-app.git'
  }
  stage('Compile-Package') {
   sh 'mvn package' 
  }


}
