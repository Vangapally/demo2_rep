pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/Vangapally/demo2_rep.git'
}
}
steps('build')
{
steps{
sh 'javac https://github.com/Vangapally/demo2_rep.githello.java'
}
}
stage('run')
{
  steps
  {
sh 'java hello'
}
}
}

