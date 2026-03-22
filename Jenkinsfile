Pipeline{
    agent any

    stages {
        stage('Maven Build') {
            steps {
                sh 'mvn clean'
                sh 'mvn install'
                // Add your build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy commands here
            }
        }
    }
}
