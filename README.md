"# quickstart-akka-iot" 

This is sample IOT application built based on the nice tutorial at http://doc.akka.io/docs/akka/current/scala/guide/tutorial_1.html

You can setup your environment for scala if not already done. Steps to follow:
	1) Install Scala following the instruction at - https://www.scala-lang.org/download/
	2) Install/Setup Environment for Scala. You can follow the document here https://github.com/quickstartall/quickstart-environmentsetup-scala
	3) Clone/Download the project and Import it to eclipse (If you want to work on it)
	4) Run the application in either of the following way (for screen shots you can refer the document - quickstartall-akka-iot-screenshots.doc)
		4.1 Run the program using sbt 
		a) go to the project root directory (e.g. C:\MyWork\Akka\quickstartall-akka-iot\quickstartall-akka-iot>)
		b) Open a command window
		c) You can optinally compile program using the command - sbt run (for offline mode - sbt "set offline := true" run)
		c) run the test  cases using command- sbt test (for offline mode - sbt "set offline :=true" test)
		
		4.2 Run the application using Eclipse
		a) import the project to eclipse as mentioned in the document in step-2
		b) In the project explorer locate the file AkkaIOTTestCases.scala under src/test/scala
		c) Right click --> Run As --> Scala Test - File
		b) All the test cases should run and you can see the output on the console.

		
