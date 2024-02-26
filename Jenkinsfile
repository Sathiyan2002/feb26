pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/Sathiyan2002/feb26.git"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java Demo.java"
	sh "python main.py"
      }
    }
  }
}
