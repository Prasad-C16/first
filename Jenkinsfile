pipeline {
    agent any

    stages {
        stage('C Program') {
            steps {
                sh 'gcc print.c -o output'
                sh './output'
            }
        }
        stage('last output') {
            steps {
                echo "end of the file"
            }
        }
    }
}
