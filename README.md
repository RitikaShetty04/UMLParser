# UMLParser

UML Parser
This project is a UML parser which converts Java Source Code into a UML Diagram.

The tools and libraries used in this project are:

Java Parser
It includes classes and interfaces which was used to parse the classes, variables, methods and constructors from the java source code.
Java parser used for this project was:
https://github.com/javaparser/javaparser
This package contains a Java 1.8 Parser with AST generation and visitor support.

PlantUML
PlantUML tool was used to draw class diagrams, sequence diagrams, usecase diagrams, activity diagrams etc. It is an Open Source project. Diagrams can be defined in a simple language. Images can be generated either in PNG, SVG or LaTeX format.
Plugin of PlantUML for eclipse was used
http://plantuml.com/

Graphviz
Graphviz (Graph Visualization Software) tool is required when using PlantUML to draw diagrams. Graphviz is a package of open-source tools developed by AT&T Labs Research for drawing graphs specified in DOT language scripts. 
http://www.graphviz.org/

Eclipse IDE
Eclipse IDE was used as the development environment for writing the code for the UML parser.
Eclipse SDK is free and open-source software. 
Version used was Eclipse Mars (4.5)
https://eclipse.org/

External JARs used:
javaparser-core-2.3.0.jar
plantuml.jar
net.sourceforge.plantuml.eclipse_1.1.11.7997.jar
