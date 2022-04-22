node('built-in') 
   {
    stage('continuous download') 
          {
            git 'https://github.com/SandeepReddyGoka/mvn.git'
          }
    stage('continuous build')
          {
            sh 'mvn package'
          }
    }
