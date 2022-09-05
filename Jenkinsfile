pipeline{
    agent any
    tools{
        gradle 'gradle'
    }
    stages {
        stage(“build”) {
          steps {
                echo 'building the application'
                sh 'gradle build runner'
            }
        }
        stage(“test”) {
          steps {
                echo 'test the application'
          }
        }
        stage(“deploy”) {
            steps {
                echo 'deploy the application'
            }
        }
    }
}
