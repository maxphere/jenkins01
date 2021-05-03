pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('build') {
            steps {
                //sh 'npm --version'
                echo "hello!"
                sh "echo Hello from the shell"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
