pipeline{
    agent any
      stages{
        stage("Build"){
          steps{
            sh 'npx antora --fetch antora-playbook.yml'
           }
        }
    }
}