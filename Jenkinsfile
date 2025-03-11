pipeline {
    agent any
    environment {
        PATH = "/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin" // 设置正确的 PATH
    }
    stages {
        stage('Example') {
            steps {
                sh 'echo Hello World'
            }
        }
    }
}