pipeline{
    agent any
    tools{
        gradle 'gradle-7.3.3'
    }
    stages {
        stage('build') {
          steps {
                echo 'building the application'
                bat 'gradle build'
            }
        }
        stage('test') {
          steps {
                echo 'test the application'
          }
        }
        stage('deploy') {
            steps {
                echo 'deploy the application'
            }
        }
    }
}
