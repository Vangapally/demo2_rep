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
sh 'javac hello.java'
}
}
stage('run')
{
sh 'java hello'
}
}
}
}
