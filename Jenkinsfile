pipeline {
    agent any
    stages { 
        stage('Example') {
            steps {
                echo 'Hello World'
                withEnv(['PYTHONPATH=/home/ubuntu/python']) {
                sh  'python ./case1.py'
} 
            }
        }
    }
}
