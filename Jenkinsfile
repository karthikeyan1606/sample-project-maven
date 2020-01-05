#!/usr/bin/env groovy
def appName= 'testing'
def major_version = 1.0 
node{ 
stage('cloning repo'){
  checkout scm
}
stage('Testing')
  {
    sh 'mvn clean test'
  }
stage('Build')
  {
    sh 'mvn clean install'
  }
  
}
