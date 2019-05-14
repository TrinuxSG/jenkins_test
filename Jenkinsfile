pipeline {
    agent any

    stages {
        stage('First Step') {
            steps {
                echo BUILD_NUMBER
                def changes = currentBuild.changeSets[0].collect {"${it.commitId}: ${it.msg}"} .join("\n")
                println "debug>>>>>>>"
                println changes.size()
            }
        }
    }
}
