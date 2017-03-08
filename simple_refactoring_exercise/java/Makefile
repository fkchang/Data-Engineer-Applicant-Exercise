all: junit-4.12.jar hamcrest-core-1.3.jar CodeReplacer.class CodeReplacerTest.class
	java -cp .:junit-4.12.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore CodeReplacerTest

CodeReplacerTest.class:
	javac -cp .:junit-4.12.jar  CodeReplacerTest.java

CodeReplacer.class:
	javac -cp .:junit-4.12.jar CodeReplacer.java

junit-4.12.jar:
	wget http://search.maven.org/remotecontent?filepath=junit/junit/4.12/junit-4.12.jar

hamcrest-core-1.3.jar:
	wget http://search.maven.org/remotecontent?filepath=org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar



clean:
	rm -f *.class *~
