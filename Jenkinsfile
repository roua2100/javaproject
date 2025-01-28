node {
    stage('Clone') {
            git branch: 'main', url: 'https://github.com/roua2100/javaproject.git'
	        }
		    
		        stage('Build') {
			        sh '''#!/bin/bash
				        javac Main.java
					        '''
						    }
						        
							    stage('Run') {
							            sh '''#!/bin/bash
								            java Main
									            '''
										        }
											}


