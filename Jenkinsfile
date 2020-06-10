pipeline {
 agent any
 stages {
  stage ('Build') {
   steps {
    echo 'Running build Automation'
    sh './gradlew build --no-demon'
    archieveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
  }
 }
}
