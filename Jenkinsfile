pipeline {
    agent any
    stages { 
        stage('Example') {
            steps {
                echo 'Hello World'
                withEnv(['PYTHONPATH=/home/ubuntu/python']) {
                sh   pip install xmlrunner
                sh  'python ./test.py'
} 
            }
        }
    }
}
