pipeline {
    agent any
triggers {
        pollSCM('* * * * *')
    }
    stages {
    stage('Demo') {
        steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Testing"
                ls -lah
            '''
        }
    }
    stage('Sonar analysis') {
        steps {
            sh 'echo "Hel World"'
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
        post {
        always {
            emailext body: 'A Test EMail', recipientProviders: [[$class: 'DevelopersRecipientProvider'], [$class: 'RequesterRecipientProvider']], subject: 'Test'
        }
    }

}
