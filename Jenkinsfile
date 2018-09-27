node('slave-docker-04') {
checkout scm
stage('build') {
    withMaven(maven: 'Default Maven') {
        /* .. some comment .. */
    sh 'mvn clean install'
}
}
}
