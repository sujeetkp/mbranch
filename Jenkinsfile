pipeline{
  agent{
    label 'linux'
  }
  stages{
    stage("test"){
      sh '''hostname'''
      echo ${env.BRANCH_NAME}
    }
  }
}
