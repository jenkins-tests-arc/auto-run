pipeline {
    agent  any
    stages {
        stage('build') {
            steps {
                echo  'build done'
            }
        }
        stage('deployments') {
            parallel {
                stage('deploy to stg') {
                    steps {
                        echo 'stg deployment done'
                    }
                }
                stage('deploy to prod') {
                    steps {
                        echo 'prod deployment done'
                    }
                }
                stage('deploy to somewhere') {
                    steps {
                        echo 'prod deployment done'
                    }
                }
            }
        }
    }
}
