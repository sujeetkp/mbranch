pipeline{
  agent{
    label 'linux'
  }
  stages{
    stage("test"){
      steps{
        sh '''hostname'''
        echo ${env.BRANCH_NAME}
      }
    }
  }
}
