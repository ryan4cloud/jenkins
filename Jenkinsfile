pipeline {
    agent { docker { image 'maven:3.6.3' } }
    stage {
        stage('build') {
            steps {
                sh 'mv --version'
            }
        }
    }
}