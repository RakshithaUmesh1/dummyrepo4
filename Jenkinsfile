pipeline{
    agent any
     stages{
         stage("server ip"){
             steps{
                 sh '''
                     hostname -i
                     echo "hostname is:$(hostname -i)"
                     '''
             }
         }
     }
}
