def readfile;
node
{
    stage('Checkout')
    {
        git branch: 'main', url: 'https://github.com/kakedari/aproject.git'
    }
    stage('Read File')
    {
       readfile = readTrusted 'C:\\Windows\\System32\\config\\systemprofile\\AppData\\Local\\Jenkins\\.jenkins\\workspace\\Demo-Readfile\\src\\main\\resources'
       echo "Reading File"
    }
}
  
