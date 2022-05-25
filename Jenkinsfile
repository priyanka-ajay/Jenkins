pipeline{
    //agent any
    agent {label 'worker-cloud'}
    options{
        buildDiscarder(logRotator(daysToKeepStr: '7'))
        disableConcurrentBuilds()
        retry(3)
        timeout(time: 1, unit: 'MINUTES')
    }
    stages{
        stage('Unit Testing'){
            steps{
                sh "echo hello C32"
            }
        }
        stage('Build '){
            steps{
                sh "echo hello C32"
                sh "sleep 9"
            }
        }
    }
}
