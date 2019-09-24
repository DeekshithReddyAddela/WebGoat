node{
  stage('scm check'){
    git 'https://github.com/DeekshithReddyAddela/WebGoat'
  }
  stage('compile'){
    def mvnHome=tool name:'maven-3', type:'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
  
    
