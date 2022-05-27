pipeline {
  agent any
   stages {
     stage("build") {
      step {
        script {
          def test = 2 + 2 > 3 ? 'true' : 'false'
          echo test
        }
      }
    }
  }
}
