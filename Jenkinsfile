node{
  stage('SCM-checkout'){
    git'https://github.com/hari-hara/INGSuite-1'
  }
  stage('Build')
  def = mavenHome = tool name: 'Maven', type: 'maven'
  sh "${mavenHome}/bin/mvn package"
}
