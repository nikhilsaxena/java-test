node
{
  tools {
    maven "3.6.3"
  }
  stage('Clean-up')
  {
    deleteDir()
  }
<<<<<<< HEAD
  stage('Maven-Check')
  {
    sh 'mvn
=======
  stage
  {
    sh "mvn -version"
>>>>>>> 45e79d9f7e473b1d8854a0a84745ff5bc772d46e
  }
  stage('Git Checkout')
  {
    git 'https://github.com/nikhilsaxena/java-test'
  }
  stage('Compile-Package')
  {
<<<<<<< HEAD
    script
	 {
      sh 'mvn package'
     }
=======
     sh "mvn package"
>>>>>>> 45e79d9f7e473b1d8854a0a84745ff5bc772d46e
  }
}
