

Web Engineering Assignment

Advantages of XML : -

1- XML uses human, not computer, language. XML is readable and understandable, even by novices, and no more difficult to code than HTML.

2- XML is completely compatible with Java™ and 100% portable. Any application that can process XML can use your information, regardless of platform.

3- XML is extendable. Create your own tags, or use tags created by others, that use the natural language of your domain, that have the attributes you need, and that makes sense to you and your users.

4- XML can be used to create new internet languages

5- XML increases data availability, different applications can access your data, not only in HTML pages, but also from XML data sources.

Disadvantages of XML : -

1- XML syntax is redundant or large relative to binary representations of similar data.
2- The redundancy may affect application efficiency through higher storage, transmission and processing costs.
3- XML syntax is too verbose relative to other alternative ‘text-based’ data transmission formats.
4- No intrinsic data type support: XML provides no specific notion of “integer”, “string”, “boolean”, “date”, and so on.
5- The hierarchical model for representation is limited in comparison to the relational model or an object oriented graph.
6- Expressing overlapping (non-hierarchical) node relationships requires extra effort.
7- XML namespaces are problematic to use and namespace support can be difficult to correctly implement in an XML parser.
8- XML is commonly depicted as “self-documenting” but this depiction ignores critical ambiguities.

Advantages of Annotations: -

1- The configuration is checked to some degree by the type system. Thus, it's impossible to misspell the name of a configuration attribute when using annotation-based configuration because that results in a compilation error. On the other hand, XML-based configuration is susceptible to this.

2- Using your IDE's help popup, you can quickly look up the documentation for a particular configuration attribute within the editor. With XML configuration, you have to refer to the website.

3- You can refactor annotation-based configuration literally by moving a block of code containing configuration annotations to another component, and this automatically moves the configuration.

4- The configuration of a component is inline with the component being configured. You don't have to remember the two (or more) different locations of files that affect the same component. Think of Javadoc and how it allows programmers to specify the documentation for a Java class and its methods inline with the source code of the class, and now imagine that instead of Javadoc, programmers needed to maintain a separate XML document containing the documentation for a project's public classes, methods, and fields. You can imagine how difficult that would be.

5- Because annotations are Java code, there is no need to "switch" between writing Java and XML.

6- Using the IDE's "find references" feature, you can quickly see if the project is using a particular configuration attribute


Disadvantages of Annotations: -

Other disadvantage of putting annotations in classes is that you will have to recompile a lot more once you want to change some requirements or if you want to have different configurations between development, test and production stages. 

















Asher Ahsan
CS131008
