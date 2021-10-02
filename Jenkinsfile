node{
  stage('SCM Checkout'){
  git 'https://github.com/rsingh040/jenkins-sonarqube.git'
  }
  stage('Compile-Package'){
   sh'mvn package'
  }

}
