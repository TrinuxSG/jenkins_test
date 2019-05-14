pipeline {
    agent any

    stages {
        stage('First Step') {
            steps {
                def causes = currentBuild.rawBuild.getAction(hudson.model.CauseAction)
            }
        }
    }
}
