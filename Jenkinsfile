node('built-in') 
   {
    stage('continuous download_master') 
          {
            git 'https://github.com/SandeepReddyGoka/mvn.git'
          }
    stage('continuous build_master')
          {
            sh 'mvn package'
          }
    }
