@Library('pipeline-library-demo') _

def config = [name: 'Dany', dayOfWeek: 'Friday']

pipeline {
    agent any
    stages {
        stage('Demo') {
            steps {
                echo 'Hello world'
                sayHello(config)
            }
        }
    }
}
