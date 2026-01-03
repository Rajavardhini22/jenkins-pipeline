pipeline{
	agent any
	stages{
		stage("Pull Code"){
			steps{
				echo "Pulling code from GitHub...."
			}
		}
		stage("Build") {
			steps {
				echo "Building Packaged from Code ...."
			}
		}
		stage("Test"){
			steps{
				echo "Testing Packaged ...."
			}
		}
		stage("Deploy") {
			steps{
				echo "Deploying Application ...."
			}
		}
	}
	}
