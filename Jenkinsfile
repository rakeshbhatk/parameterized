pipeline {
agent any
parameters {
string(name: 'branch', defaultValue: 'dev', description: 'Branch selected')
}
stages {
stage('Trigger pipeline') {
  when 
  { 
    branch 'master'
   
   echo "deploy master to the stage" }
   
   when {
     branch 'dev'
     echo "deploy dev to the stage"
   }
   

}
}
}
