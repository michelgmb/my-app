node{


  stage('SCM Clone'){
    git 'https://github.com/michelgmb/my-app.git'

  }
  stage('Compile-Package'){
    sh 'mvn clean package'
    sh 'mvn package'

  }

}
