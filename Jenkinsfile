pipeline {
  agent any
    stages {
      stage ('validate') {
        steps {
          git 'https://github.com/satishhari1234/jenkinsfile.git'
          sh 'mvn validate'
          echo 'validating'
          }
          }
          stage ('compile') {
        steps {
          git 'https://github.com/satishhari1234/jenkinsfile.git'
          sh 'mvn compile'
          echo 'compiling'
          }
          }
          stage ('test') {
        steps {
          git 'https://github.com/satishhari1234/jenkinsfile.git'
          sh 'mvn test'
          echo 'testing'
          }
          }
          stage ('package') {
        steps {
          git 'https://github.com/satishhari1234/jenkinsfile.git'
          sh 'mvn package'
          echo 'packaging'
          }
          }
          }
          }
