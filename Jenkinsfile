pipeline {
    agent any
    stages{
        stage('Install From ISO'){
            steps {
                sh 'echo "This is the install from iso stage"'
                sh 'echo "    Installing ..."'
                sh 'echo "    Done"'
            }
            post {
                success {
                   sh 'echo "The install from iso stage was successful"'
                }
            }
        }
        stage('Setup'){
            steps {
                sh 'echo "This is the setup stage"'
                sh 'echo "    license"'
                sh 'echo "    files"'
                sh 'echo "    users"'
                sh 'echo "    snapshot"'
                sh 'echo "    Done"'
            }
            post {
                success {
                   sh 'echo "The setup stage was successful"'
                }
            }
        }
        stage('Configure'){
            steps {
                sh 'echo "This is the configure stage"'
                sh 'echo "    users"'
                sh 'echo "    policy"'
                sh 'echo "    file install"'
                sh 'echo "    keys install"'
                sh 'echo "    snapshot"'
                sh 'echo "    commit"'
                sh 'echo "    Done"'
            }
            post {
                success {
                   sh 'echo "The confiure stage was successful"'
                }
            }
        }
        stage('Test'){
            steps {
                sh 'echo "This is the test stage"'
                sh 'echo "    pings"'
                sh 'echo "    single scp"'
                sh 'echo "    quick test"'
                sh 'echo "    all files test"'
                sh 'echo "    Done"'
            }
            post {
                success {
                   sh 'echo "The test stage was successful"'
                }
            }
        }
    }
}
