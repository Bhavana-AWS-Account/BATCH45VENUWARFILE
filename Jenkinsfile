node('master') 
{
   stage('CD-S1-Git') 
   {
    git 'https://github.com/BABJI-AWS-DEVOPS/BATCH45VENUWARFILE.git'
   }
}
node('master')
{
    stage('CD-S2-MVN') 
     {
     sh 'mvn package'
     }
}
