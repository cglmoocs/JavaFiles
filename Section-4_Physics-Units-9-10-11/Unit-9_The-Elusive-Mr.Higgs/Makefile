JAVAC=javac
JVM=java
CLASSPATH=".:$(HOME)/Dependencies/*"
sources = $(wildcard *.java)
classes = $(sources:.java=.class)

PRG1=HiggsClassISloping
PRG2=HiggsClassIIUniform

all: $(classes)

run :
	$(JVM) -classpath $(CLASSPATH) $(PRG1)
	$(JVM) -classpath $(CLASSPATH) $(PRG2)

clean :
	rm -f *.class

%.class : %.java
	$(JAVAC) -classpath $(CLASSPATH) $<
