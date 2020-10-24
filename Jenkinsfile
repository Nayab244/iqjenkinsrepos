node('master') 
{
   stage('ContinuosDownload_master') 
   {
    git 'https://github.com/Nayab244/maven.git'
   }
   stage('ContinuosBuild_master') 
   {
    sh 'mvn package'
   }
}
   
