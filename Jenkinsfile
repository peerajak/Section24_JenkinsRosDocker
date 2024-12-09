  pipeline {
      agent any 
      stages {
          stage('Print + list current directory') {
              steps {
                  sh 'pwd'
                  sh 'ls -al'
              }
          }
          stage('Show ROS environment variables') {
              steps {
                  sh 'env | grep ROS'
              }
          }
          stage('Done') {
              steps {
                  sleep 5
                  echo 'Pipeline completed'
              }
          }
      }
  }