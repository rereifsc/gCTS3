pipeline {
  agent any
  stages {
    stage('build'){
      build 'gCTS-Pipeline'
    }
    stage('gctsCreateRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        gctsCreateRepository script: this
      }
    }

    stage('gctsCloneRepository') {
      steps {
        // One or more steps need to be included within the steps block.
        gctsCloneRepository script: this
      }
    }

}




