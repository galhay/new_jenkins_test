pipeline {
    agent any
    
       triggers {
        cron('* * * * *')
    }

    stages {
        stage('Hello') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
