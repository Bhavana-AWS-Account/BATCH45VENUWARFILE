{
   stage('CD-S1-Git-payment') 
   {
    git 'https://github.com/Bhavana-AWS-Account/myweb.git'
   }
}
node('master') {
    stage('CD-S2-MVN-payment') 
     {
     sh 'mvn package'
     }
}
