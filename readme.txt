pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
<<<<<<< HEAD
Creating a new branch is quick & simple。
=======
Creating a new branch is quick.
Creating a new branch is quick AND simple.
>>>>>>> featurel
