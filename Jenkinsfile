pipeline {
 agent any
  
 stages {
  
  
  stage ('Compile Stage') {  
  steps {
  withMaven(maven : 'maven_3_3_5') {
     sh 'mvn clean compile'
  }
  }
  } 
 }
}
