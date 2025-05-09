pipeline {
    agent none
        stages {
            stage('checkout-stage') {

                agent {
                    label 'worker1'
                }
                steps {
                    echo "This is my first pipeline joffffff" 
                }
            }

            stage('BUILD') {

                agent {
                    label 'worker1'
                }

                steps {
                    echo "This build stage"
                }
            }
        }
}
