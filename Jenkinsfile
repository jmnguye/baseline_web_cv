pipeline {
    agent any
    stages {
        stage('Build image') {
            steps {
                sh 'docker build /var/jenkins_home/workspace/web_cv_pipeline/django -t test1'
            }
        }
    }    
}
