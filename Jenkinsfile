#Comment
pipeline {
     agent { label 'java' }

    stages {
        stage('git clone') {
            steps {
              git 'https://github.com/Kumarbgm16/java-azure-project.git'
            }
        }
        stage('build') {
            steps {
              sh "mvn clean package"
            }
        }
    }
}
