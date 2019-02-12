node{
  stage('SCM Checkout'){
   git 'https://github.com/GeorgiDimitrov19/jenkins-file'
  }
   stage('Compile-Package'){
   sh 'mvn package'
  }
}
