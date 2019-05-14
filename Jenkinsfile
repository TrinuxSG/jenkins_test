pipeline {
    agent any

    stages {
        stage('First Step') {
            steps {
                script {
                GIT_COMMIT_HASH = sh (script: "git log -n 1 --pretty=format:'%H'", returnStdout: true)

                echo "**************************************************"
                echo "${GIT_COMMIT_HASH}"
                echo "**************************************************"
    }
            }
        }
    }
}
