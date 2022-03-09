def readfile;
node
{
    stage('Checkout')
    {
        git branch: 'main', url: 'https://github.com/kakedari/aproject.git'
    }
    stage('Read File')
    {
       readfile = readTrusted '/target/classes/textfile.txt'
       echo "Reading File"
    }
}
  
