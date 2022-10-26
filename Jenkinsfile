pipeline {
   agent any
   environment {
     BRANCH_NAME = "${GIT_BRANCH.split("/")[1]}"
  }

    stages {
        stage('Build') {
            steps {
                   
                   echo "hi the branch is ${BRANCH_NAME}"
                   sh 'printenv'

            }
   
        }
    }
}
