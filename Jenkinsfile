pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                echo "This is pipeline build trigger"
                set PATH='C:\\Python27\\Scripts'
                python '--version'
            }
        } 
        stege('deploy'){
            steps { 
                echo "This is pipeline consist of stage trigger"
            }
        }
    }
}
