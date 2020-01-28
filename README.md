# Enkel

[![Build Status](https://travis-ci.org/JakubDziworski/Enkel-JVM-language.svg?branch=master)](https://travis-ci.org/JakubDziworski/Enkel-JVM-language)

Enkel is a simple programming language running on the  jvm

# [Blog - Creating JVM Language] (http://jakubdziworski.github.io/categories.html#Enkel-ref)
 Since day one I've been describing whole project development process on my [blog post series - Creating JVM Language] (http://jakubdziworski.github.io/categories.html#Enkel-ref). 
It consist of 20 posts covering all the issues.
When in doubt browsing the code, I encorouge you to take a look at the blog.

## Compiling and running Enkel scripts
1.Build compiler into executable jar

```bash
mvn clean package
```
2.Compile sample .enk file (You can find more examples in EnkelExamples directory)

```bash
java -classpath compiler/target/compiler-1.0-SNAPSHOT-jar-with-dependencies.jar:. com.kubadziworski.compiler.Compiler EnkelExamples/DefaultParamTest.enk
```

3.Run compiled .enk program

```bash
java DefaultParamTest
```
