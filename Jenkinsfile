pipeline {
    agent none
        stages {
            stage('checkout') {

                agent {
                    label 'worker1'
                }
                steps {
                    echo "This is my first pipeline joffffff" 
                }
            }

            stage('BUILD') {

                steps {
                    echo "This build stage"
                }
            }
        }
}
