#!/usr/bin/env groovy

pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Build'
        archiveArtifacts artifacts: '**/target/*.jar', fingerprint:true
      }
    }
  }
}
