pipeline {
			agent any 
			stages {
				stage('Build') {
					steps {
					sh 'sleep 1; echo "this is build stage"'
					}
				}
				stage('test'){
					steps {
					sh 'sleep 1; echo "this is test stage"'
					}
				}
				stage('depoloy'){
					steps {
					sh 'sleep 1; echo "this is deploy stage"'
					}
				}
				stage('my-own-work'){
					steps {
					sh 'sleep 1; echo "this is my stage"'
					}
				}	
			}
			}
