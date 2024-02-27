pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/Sathiyan2002/feb26"
      }
    }
    stage("Run")
    {
      steps
      {
        "javac Demo.java"
        "java Demo"
      }
    }
  }
}
