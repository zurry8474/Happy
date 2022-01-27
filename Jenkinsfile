pipeline {
    agent any
    tools {
        gradle 'Gradle-7.1.1'
    }
    stages {
        stage('run backend') {
            steps {
                echo 'executing gradle'
                    sh 'chmod +x gradlew'
                    sh './gradlew -v'
            }
        }
    }
}
