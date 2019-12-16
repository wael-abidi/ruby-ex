pipeline {
    agent { docker { image 'dockerproxy-cwfr1.rd.francetelecom.fr/ruby' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
    }
}
