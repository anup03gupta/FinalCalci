node {
   stage('SCM Checkout') {
  git 'https://github.com/anup03gupta/FinalCalci.git'

}
   stage('Build') {
      def mvn_version = 'maven'
      withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
      bat label: '', script: 'mvn install -Dmaven.test.skip=true'
}
    
	   
}
 stage('Deploy'){
input message: 'Proceed or Abort', submitter: 'Anup'

}
}
