JAVAC=javac
CLASSPATH=".:$(HOME)/Dependencies/*"
sources = $(wildcard *.java)
classes = $(sources:.java=.class)

all: $(classes)

clean :
	rm -f *.class

%.class : %.java
	$(JAVAC) -classpath $(CLASSPATH) $<
