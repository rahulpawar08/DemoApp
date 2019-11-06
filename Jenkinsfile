pipeline {
     agent { label 'master' }
     parameters{
     choice(
        name: 'Environment',
        choices: "Refresh\nBuild\nQA\nStage\nProd",
        description: 'Please select the pipeline action'
      )
   } 
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('QA') {
            steps {
                echo 'Deployed on QA..'
            }
        }
        stage('Stage') {
            steps {
                echo 'Deployed on Stage....'
            }
        }
        stage('Prod') {
            steps {
                echo 'Deployed on Prod....'
            }
        }
    }
}