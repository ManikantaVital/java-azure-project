pipeline {
     agent { label 'java' }

    stages {
        stage('git clone here happen remove this') {
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
