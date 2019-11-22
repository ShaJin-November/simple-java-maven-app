pipeline {
    agent {
        label 'ALDNDEVC'
    }
    stages {
        stage('Build') {
            steps {
                sh 'cd /home/sjin_x'
            }
        }
        stage('Test') {
            steps {
                sh 'system -kpeb dsplibl'
            }
        }
        stage('Deliver') {
            steps {
                sh 'cp /home/sjin_x/workspace/workspace.txt /home/sjin_x'
            }
        }
    }
}
