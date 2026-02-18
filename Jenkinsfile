pipeline{
  agent {
    label 'master'
  }
  stages{
    stage('Branch Test'){
      steps{
        echo "the branch is ${env.BRANCH_NAME}"
      }
    }
  }
}
