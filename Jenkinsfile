pipeline 
{
  agent any
   parameters {
    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
   }
stages {
  stage('Example') {
      steps {
        echo "Hello ${params.PERSON}"
          echo "Toggle: ${params.TOGGLE}"
      }
  }
}
  
}
