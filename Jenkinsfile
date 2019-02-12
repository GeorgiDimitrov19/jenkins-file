node{
  stage('SCM Checkout'){
    tool name: 'maven-3', type: 'maven'
   git 'https://github.com/GeorgiDimitrov19/jenkins-file'
  }
   stage('Compile-Package'){
   sh 'mvn package'
  }
}
