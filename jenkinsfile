pipeline {

 agent any

 tools {jdk 'JAVA_HOME’, maven 'maven_home'}

 stages {

 stage('GIT') {

           steps {

               git branch: 'main',

               url: ' https://github.com/hafsioussema/oussemahafsi4sim3.git'

          }

     }

 stage ('Compile Stage') {

 steps {

 sh 'mvn clean compile'

 }

 }

 }

}