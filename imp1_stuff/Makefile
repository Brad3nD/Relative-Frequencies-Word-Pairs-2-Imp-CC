
default: 
	javac *.java
	jar -cvf relativefreq1.jar ./*.class
	hadoop jar relativefreq1.jar relativefreq1 input output

clean:
	rm -rf output *.jar *.class

clobber:
	rm -rf output *.jar *.class *.java
