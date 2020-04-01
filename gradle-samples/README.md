
Gradle Samples

## Table of Contents

* [Hello Gradle world example](#hello-gradle-world-example)
* [Project properties example](#project-properties-example)
* [Various ways to define tasks](#various-ways-to-define-tasks)


## Hello Gradle world example

1. Run below command to display output of Hello Gradle world example

	**gradle -q -b hello-gradle-world.gradle helloGradleWorld**    <br/>
			**or**  <br/>
	**.\gradlew -q -b hello-gradle-world.gradle helloGradleWorld**  <br/> <br/>
	
2. Below is the output of Hello Gradle world example 

		 helloGradleWorld!!
   

## Project properties example

1. Run below command to display output of Project properties example

	 **gradle -q -b project-properties.gradle displayProjectDetails**    <br/> 
				**or** <br/>
	 **.\gradlew -q -b project-properties.gradle displayProjectDetails**  <br/> <br/>
	
2. Below is the output of Project properties example

		project name is ----> gradle-samples   
		project description is ----> Test project description   
		project group is ----> org.gradle.api   
		project version is ----> 0.0.1    


## Various ways to define tasks

1. 	Run below command to display configurations of tasks 

	 **gradle -q -b various-ways-to-define-tasks.gradle**    <br/>
			**or**  <br/>
	**.\gradlew -q -b various-ways-to-define-tasks.gradle**  <br/> <br/>
	 
	 
2.  Below is the output of running above command 	

		It's taskA configuration
		It's taskB configuration


	 