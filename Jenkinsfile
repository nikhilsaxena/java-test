node
{
  tools {
    maven "3.6.3"
  }
  stage('Clean-up')
  {
    deleteDir()
  }
  stage('Git-Checkout')
  {
    git 'https://github.com/nikhilsaxena/java-test'
  }
  stage('Maven-Version')
  {
    sh 'mvn -v'
  }	
}
