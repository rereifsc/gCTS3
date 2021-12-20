
pipeline {
  libraries {
    lib('piper-lib-os')
  }
  agent any
  stages {
    stage('CreateRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        @Library('piper-lib-os')
        gctsCreateRepository script: this
      }
    }

    stage('CloneRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        @Library('piper-lib-os')
        gctsCloneRepository script: this
      }
    }

}




