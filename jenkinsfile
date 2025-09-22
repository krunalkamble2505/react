pipeline {
    agent any

    tools{
      nodejs 'nodejs'
    }

    stages {
        stage('NPM install') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }


    }

}
