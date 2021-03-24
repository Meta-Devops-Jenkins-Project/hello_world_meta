node{
 stage("SCM Checkout"){
  git "https://github.com/Meta-Devops-Jenkins-Project/hello_world_meta.git"
 }
 stage("Compile-Package"){
  sh "mvn package"
 }
}
