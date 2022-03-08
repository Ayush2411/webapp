pipeline {
    agent {
    node {
        label 'my-defined-label'
       
    }
}
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
