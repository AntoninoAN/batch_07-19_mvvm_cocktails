pipeline{
    agent any
    tools{
        gradle 'gradle'
    }
    stages {
        stage(“build”) {
          steps {
                echo 'building the application'
                sh './gradlew -v'
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
