node {
 stage('SCM git checkout')
 {
   git 'https://github.com/rameshmishra777/maven-samples'
 }
stage('Compile and package through maven')
{
  def mvnHome= tool name: 'maven', type: 'maven'
  sh "${mvnHome}/bin/mvn clean package"
}

}
