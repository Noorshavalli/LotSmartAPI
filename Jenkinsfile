pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                echo "This is pipeline to build trigger"
                cd "C:\\Python27\\"
                set PATH='C:\\Python27\\Scripts'
                python '--version'
                python '-m hello.py'
            }
        } 
        stage('deploy'){
            steps { 
                echo "This is pipeline consist of stage trigger"
            }
        }
    }
}
