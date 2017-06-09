pipeline {
  agent any
  stages {
    stage('Recovering Host') {
      steps {
        build 'THC_CG_Pipeline_to_recover_single_node'
      }
    }
    stage('Build Code') {
      steps {
        build 'THC_CG_build'
      }
    }
  }
}