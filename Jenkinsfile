pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        sh 'echo Hello World 1!!'
      }
    }
    stage('Stage 2') {
      steps {
        echo 'Ritu is working on Blue Ocean'
      }
    }
    stage('Stage 3') {
      steps {
        mail(subject: 'Blue ocean demo', body: 'hi..working on creating a pipeline', from: 'rituverma.rv22@gmail.com', to: 'rituverma.rv22@gmail.com')
      }
    }
  }
}