node {
   stage('SCM Checkout') {
  git 'https://github.com/anup03gupta/FinalCalci.git'

}
   stage('Build') {
    bat label: '', script: 'mvn -f C:\\dev\\code\\5-5-20\\ejm\\EJMWebMVC install -Dmaven.test.skip=true'
	   
}
 stage('Deploy'){
input message: 'Proceed or Abort', submitter: 'Anup'

}
}
