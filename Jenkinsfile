@Library('piper-lib-os') _
pipeline {
  libraries {
    lib('piper-lib-os')
  }
  agent any
  stages {
    stage('CreateRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        gctsCreateRepository script: this
      }
    }

    stage('CloneRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        gctsCloneRepository script: this
      }
    }

}




