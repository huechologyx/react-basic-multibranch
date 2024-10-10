pipeline {
    agent {label "linux"}
    options {
        buildDiscard logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', artifactDaysToKeepStr: '', numToKeepStr: '5')
        disableConcurrentBuilds()
    }

    stages {
        stage('Hello') {
            steps {
                echo "Hello"
            }
        }
    }
}