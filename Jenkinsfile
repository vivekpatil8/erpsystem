pipeline {
  agent any
   stages {
     stage("build") {
      step {
        echo 'building app'
        script {
          def test = 2 + 2 > 3 ? 'true' : 'false'
          echo test
        }
      }
    }
  }
}
