node{
  stage('SCM Checkout'){
  git 'https://github.com/rsingh040/jenkins-sonarqube.git'
  }
  stage('Compile-Package'){
    //Get maven home path
    def mvnHome = tool name: 'newmaven', type: 'maven'  
    sh "${mvnHome}/bin/mvn package"
  }

}
