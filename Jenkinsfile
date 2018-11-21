node{
   stage('scm checkout'){
    git 'https://github.com/vinaygit1/my-app.git'
  }
   stage ('complie the package'){
     def mvnHome=tool name: 'maven-3', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
  } 

}
