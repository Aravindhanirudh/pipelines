pipeline {
	agent any
	environment {
		myName="aravindh"
}
	stages{
		stage (myFirstStage) {
			steps {

				println myName
			}

		}
		stage (mySecondStage) {
			steps {

				println "hey there am at 2nd stage"
			}

		}
		stage (scriptingStage) {
			steps {

				sh '''
				echo "this is from 
				shell script"

				''' 
			}

		}
		stage (fourthStage) {
			steps {

			println "this is fourth stage"

			}

		}




	}
}
