pipeline {
     agent any
     stages {
         stage('Build') {
              steps {
                  sh 'echo "Hello World"'
                  sh '''
                         echo "Multiline shell scripts work too"
                         ls -lah
                      '''                       
              }
         }
        stage('Lint HTML') {
             steps {
                  sh ‘tidy -q -e *.html’
                   }
          }
   }
}
