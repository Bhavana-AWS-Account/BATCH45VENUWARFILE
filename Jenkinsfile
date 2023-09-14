node('master')
{
   stage('CD-S1-Git')
   {
    git 'https://github.com/Bhavana-AWS-Account/myweb.git'
   }
}
node('master') 
{
    stage('CD-S2-MVN') 
     {
     sh 'mvn package'
     }
}
