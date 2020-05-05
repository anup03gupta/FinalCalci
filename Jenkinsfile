node {
   stage('SCM Checkout') {
  git 'https://github.com/anup03gupta/FinalCalci.git'

}
   stage('Build') {
    bat label: '', script: 'mvn install -Dmaven.test.skip=true'
	   
}
 stage('Deploy'){
input message: 'Proceed or Abort', submitter: 'Anup'

}
}
