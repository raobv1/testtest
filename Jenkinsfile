pipeline{
  agent none 
  stage(' Cloning Repo){
        when{
          branch 'develop'
        }
        steps{
          script{
            try{
              echo "Clonning Develop repo"
            }
            catch(err){
              echo "Errored"
            }
          }
          
        }
  }
}
