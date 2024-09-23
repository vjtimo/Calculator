   pipeline {
       agent any
       stages {
           stage('Build') {
               steps {
                   git 'https://github.com/vjtimo/Calculator.git'
                   bat 'mvn clean install'
               }
           }
       }
   }
