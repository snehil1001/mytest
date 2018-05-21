pipeline {
    agent any
    stages { 
        stage('Example') {
            steps {
                echo 'Hello World'
                withEnv(['PYTHONPATH=/home/ubuntu/python']) {
                pip install xmlrunner
                sh  'python ./test.py'
} 
            }
        }
    }
}
