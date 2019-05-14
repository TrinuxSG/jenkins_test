pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        def changes = currentBuild.changeSets[0].collect {"${it.commitId}: ${it.msg}"} .join("\n")
        println "debug>>>>>>>"
        println changes.size()
        println BUILD_NUMBER
      }
    }
  }
