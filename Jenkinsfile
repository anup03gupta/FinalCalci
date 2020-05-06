node {
   stage('SCM Checkout') {
  git 'https://github.com/anup03gupta/FinalCalci.git'

}
   stage('Build') {
       bat label: '', script: 'mvn install -Dmaven.test.skip=true'
}
 stage('Deploy'){
input message: 'Proceed or Abort', submitter: 'Anup'
bat label: '', script: 'copy C:\\Windows\\System32\\config\\systemprofile\\AppData\\Local\\Jenkins.jenkins\\workspace\\ejm_dev\\target\\Calculator_dev.war D:\\JBoss\\standalone\\deployments\\'

}
 
}
