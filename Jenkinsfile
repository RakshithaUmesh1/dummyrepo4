pipeline{
    agent any{
        label 'node-1'
    }
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
