pipeline {
   agent any
	stages {
      stage('Git Checkout') {
         steps {
            sh 'echo CHECKOUT'
		}
	}
	stage('Build') {
		steps {
			sh 'echo BUILD'
			}
		}
	}
	stage("Quality Gate") {
            steps {
             sh 'echo QGATE'
            }
          }
	stage ('Deploy') {
		steps {
			sh 'echo DEPLOY'
		}
	}
	stage ('Release') {
		steps {
			sh 'echo RELEASE'
		}
	}
}
}
