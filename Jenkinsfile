pipeline {
    agent any

    stages {
        stage('First Step') {
            steps {
                script {
                GIT_COMMIT_HASH = sh "(git log -n 1 --pretty=format:'%H')"

                echo "**************************************************"
                echo "${GIT_COMMIT_HASH}"
                echo "**************************************************"
    }
            }
        }
    }
}
