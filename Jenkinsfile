pipeline{
    agent any
    stages{
        stage('clonee')
        {
            steps{
                git  url: 'https://github.com/Rupali1520/secrepo.git'
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

