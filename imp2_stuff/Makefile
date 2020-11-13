
default: 
	javac *.java
	jar -cvf relativefreq2.jar ./*.class
	hadoop jar relativefreq2.jar relativefreq2 input output

clean:
	rm -rf output *.jar *.class

clobber:
	rm -rf output *.jar *.class *.java
