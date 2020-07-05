pipeline
agent any
{
stages
{

stage ('git clone')
  { steps
   {sh 'echo downloading code'}   
  }
  
  stage ('code compile')
  {steps
  { sh 'echo is compiling' }
  }
  
stage ('code build')
  { steps
   {sh 'echo build'}
  }
  stage ('code delpoy')
  {steps
   { sh 'echo deploy'}
  
  }
}
}
