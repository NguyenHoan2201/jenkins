pipeline {
  agent any
  stages{
    stage('main'){
      when{
        branch 'main'
      }
      steps {
        echo 'build main'
      }
    }
    
    stage('dev'){
      when{
        branch 'dev'
      }
      steps {
        echo 'build dev'
      }
    }
  }
}
