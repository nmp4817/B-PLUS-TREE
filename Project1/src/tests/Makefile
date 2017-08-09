JAR=btreelib.jar

#this is the name of the given project folder
ASSIGNMENT=Project1

#change the ASSIGN path with your path
ASSIGN=/home/n/nm/nmp4817

#change the JDKPATH if you are not using omega.uta.edu
JDKPATH = /opt/jdk1.6.0_20
LIBPATH = $(ASSIGN)/$(ASSIGNMENT)/lib/$(JAR)

LIBPATH = $(ASSIGN)/$(ASSIGNMENT)/lib/$(JAR)
CLASSPATH = $(LIBPATH):$(ASSIGN)/$(ASSIGNMENT):$(ASSIGN)/$(ASSIGNMENT)/src
BINPATH = $(JDKPATH)/bin
JAVAC = $(JDKPATH)/bin/javac -classpath $(CLASSPATH)
JAVA  = $(JDKPATH)/bin/java  -classpath $(CLASSPATH)

BTTest:BTTest.java
	$(JAVAC) BTTest.java TestDriver.java

bttest: BTTest
	$(JAVA) tests.BTTest

clean:
	\rm -f *.class *~ \#* core 
