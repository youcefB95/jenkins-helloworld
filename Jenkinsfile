node {
  stage('clone') {
    git branch: 'main', url: 'https://github.com/youcefB95/jenkins-helloworld.git'
   
}  
  stage('build') {

    sh 'javac Main.java'
   
 
}  
  stage('run') {
   sh 'java Main'
 
}  
}
