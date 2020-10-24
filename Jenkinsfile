node('master') 
{
   stage('ContinuosDownload_loans') 
   {
    git 'https://github.com/Nayab244/maven.git'
   }
   stage('ContinuosBuild_loans') 
   {
    sh 'mvn package'
   }
}
   
