pipeline {
  agent any
  stages {
    stage('Register new Task Defenition') {
      steps {
        sh 'aws ecs register-task-definition --cli-input-json file://task_definition.json --tags new' 
      }
    }
   
    }
}
