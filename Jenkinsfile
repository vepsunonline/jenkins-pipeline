pipeline {
   agent any

   stages {
      stage('src') {
         steps {
            sh 'sudo docker run -itd --name c1 centos'
         }
      }
      stage('build'){
          steps {
              sh 'sudo docker run -itd --name c2 ubuntu'
          }
      }
   }
}
