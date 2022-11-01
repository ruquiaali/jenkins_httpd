pipeline {
    agent any
  
    stages  {
        stage('check the status of apache') {
            steps {
                sh 'systemctl status apache2'
            }
        }
        stage('copy index.html to your apache home directory') {
            steps {
                sh 'cp index.html /var/www/html/'
            }
        }
 }
}
