pipeline{
    agent any
    stages{
        stage('clone')
        {
            steps{
                git credentialsId: '7cc4e9f4-3ab2-4d0a-b21f-3337da4d721d', url: 'https://github.com/Rupali1520/secrepo.git'
            }
        }
        stage('build')
       { 
        steps{
            sh 'python 1.py'
        }
      }
        
    }
}

