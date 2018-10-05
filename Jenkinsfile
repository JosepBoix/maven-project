pipeline{
 agent any
 stages{
 	stage ('Build'){
 		steps{
 			bat 'set JAVA_HOME=C:\\Users\\josep.boix\\AT\tools\\jdk1.8.0_74\\jdk1.8.0_74'
 		}
 		steps{
 			bat 'C:\\Users\\josep.boix\\AT\\tools\\apache-maven-3.5.0\\bin\\mvn clean package'
 		}
 	}
 }
}