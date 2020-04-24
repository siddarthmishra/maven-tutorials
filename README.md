Maven Reference Manual - http://maven.apache.org/guides/

Maven eBooks - https://www.sonatype.com/ebooks

Maven Cheat Sheet - https://www.jrebel.com/blog/maven-cheat-sheet

Maven Archetypes - http://maven.apache.org/archetypes

https://www.youtube.com/watch?v=0CFWeVgzsqY

mvn compile
	compile source code

mvn test-compile
	compile test source code
	
mvn clean
	delete target folder
	
mvn test
	run the junit test files
	
	
Maven Build LifeCycle
	validate
	compile
	test
	package
	integration test
	verify
	install
	deploy
	
mvn help:effective-pom

mvn dependency:tree

mvn dependency:sources
	downloads the source files of all dependencies
	
mvn help:effective-settings

mvn archetype:generate

mvn -X clean install

mvn tomcat7:run
