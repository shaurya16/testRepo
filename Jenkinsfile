pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'echo "TEST_VAR=\"Hello World\"  $TEST_VAR! Testing the sh command"'
            }
        }
    }
}
