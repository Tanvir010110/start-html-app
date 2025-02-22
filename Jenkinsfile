pipeline {

           agent any          

           stages {
                    stage('Fetch Code') {
                               steps {
                                       git branch: '', url: 'https://github.com/Tanvir010110/start-html-app.git'
                      }
              }
              stage('Install Apache') {
                               steps {
                                       sh 'sudo apt install apache2'-y
                      }
              }
              stage('Deploy App') {
                               steps {
                                       sh 'sudo cp -R * /var/www/html/'
                      }
              }
      }

}
