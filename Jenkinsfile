pipeline{
  agent any
  stages{
    stage('stage1'){
      steps{
        bat """
          java --version
          javac HelloWorld.java
          java HelloWorld
        """
      }
    }
  }
}
