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
        "javac Demo.java"
	"java Demo"
	"python main.py"
      }
    }
  }
}
