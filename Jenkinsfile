node
{
  stage('Git Checkout')
  {
    git 'https://github.com/nikhilsaxena/java-test'
  }
  stage('Compile-Package')
  {
     sh 'mvn package'
  }
}