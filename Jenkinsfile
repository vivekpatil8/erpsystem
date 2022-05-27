pipeline {
  agent any
   stages {
     stage("build") {
      steps {
        script {
          def test = 2 + 2 > 3 ? 'true' : 'false'
          echo test
        }
      }
    }
  }
}
