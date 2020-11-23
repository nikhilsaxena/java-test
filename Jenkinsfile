node
{
  tools {
    maven "3.6.3"
  }
  stage('Clean-up')
  {
    deleteDir()
  }
  stage
  {
    sh "mvn -version"
  }
  stage('Git Checkout')
  {
    git 'https://github.com/nikhilsaxena/java-test'
  }
  stage('Compile-Package')
  {
     sh "mvn package"
  }
}
