node
{
  tools {
    maven "3.6.3"
  }
  stage('Clean-up')
  {
    deleteDir()
  }
  stage('Maven-Check')
  {
    sh 'mvn
  }
  stage('Git Checkout')
  {
    git 'https://github.com/nikhilsaxena/java-test'
  }
  stage('Compile-Package')
  {
    script
	 {
      sh 'mvn package'
     }
  }
}