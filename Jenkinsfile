pipeline{
    agent{
        any
    }
    stages{
        stage('build'){
            steps{
                echo 'cloning reprositery'
            }
        }
        stage('build debug app'){
            steps{
                echo 'generating debug app'
                sh './gradlew assembleDebug'
            }
        }
    }
}