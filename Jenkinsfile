pipeline {
    agent any
triggers {
        pollSCM('* * * * *')
    }
    stages {
    stage('Test') {
        steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Testing"
                ls -lah
            '''
        }
    }
stages {
    stage('Sonar analysis') {
        steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Testing"
                ls -lah
            '''
        }
    }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
}
            stage('Upload') {
                steps {
                    sh 'echo "Hello World"'
                    sh '''
                        echo "Multiline shell steps works too"
                        ls -lah
                    '''
                }
        }
stage('Load-test') {
                steps {
                    sh 'echo "Hello World"'
                    sh '''
                        echo "Multiline shell steps works too"
                        ls -lah
                    '''
                }
        }
    }
}
