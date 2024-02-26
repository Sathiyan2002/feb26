pipeline
{
  agent any
  stages
  {
    stage("git")
    {
      steps
      {
        git "https://github.com/Sathiyan2002/feb26.git"
      }
    }
    stage("run")
    {
      steps
     {
      "java Demo.java"
      "python main.py"
      }
    }
  }
}
