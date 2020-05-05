pipeline {
	agent any
    stages{
		stage('sample-stage'){
			steps{
				println "Declarative"
				sh 'echo Hello Lucky'
				script{
					def var = "yes"
					if( var == "yes" ){
						echo "Hai Lucky"
					}
					else{
						echo "Bye Lucky"
					}
				}
			}
		}
	}
}
