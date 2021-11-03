pipeline {
    agent {
        label "kubectl"
    }
    stages {
        stage ("print") {
            steps {
                sh "printenv"
            }
        }
    }
}