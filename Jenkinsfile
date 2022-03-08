def readfile;
node
{
    stage('Checkout')
    {
        git branch: 'main', url: 'https://github.com/kakedari/aproject.git'
    }
    stage('Read File')
    {
       readfile = readTrusted 'aproject/src/main/resources'
       echo "Reading File"
    }
}
  
