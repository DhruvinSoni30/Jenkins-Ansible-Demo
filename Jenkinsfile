pipeline{
  agent any  
  stages{
    
      stage("Git Checkout"){
        steps{
          sh 'git clone <Your-Repository-URL>'
        }
      }
      
      stage("Run an ansible playbook"){
        steps{
          sh 'ansible-playook <playbook-name.yml> --vault-password- file <password file>'
        }
      }
   }
}
