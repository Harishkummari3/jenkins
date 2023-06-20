pipeline {
    agent any
    
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('second'){
            steps {
               echo 'This i a text msg'
               }
        }
        stage('three'){
            steps {
               input('do you want to procede?')
               }
        }
        stage('four'){
            steps {
               echo 'pipeline build completed...'
               }
        }
    }
}
