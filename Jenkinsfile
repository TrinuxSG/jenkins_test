pipeline {
    agent any

    stages {
        stage('First Step') {
            steps {
                echo BUILD_NUMBER
                currentBuild.rawBuild.getActions()
            }
        }
    }
}
