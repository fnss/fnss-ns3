# Fast Network Simulation Setup (FNSS) - Java library
The FNSS Java library can parse XML files of topologies, traffic matrices and event schedules generated through the core FNSS library. The parsed files are converted in Java objects that can be used in Java-based simulators.

## Project directory structure
The files of the Java FNSS library are organized in the following directories:

* bin: compiled class files (generated by the build script)
* dist: FNSS Java API built packages (generated by the build script)
* doc: Javadoc documentation (generated by the build script)
* examples: example code using the library
* lib: third-party libraries
* src: source code
* test: test code

## Build
You can build the code or the documentation or run the tests by using the [Ant](http://ant.apache.org/) build script (`build.xml`) provided in the root directory of the project. By default, this script will compile the entire code, run unit tests, create Javadoc documentation and package the library into Jar files.

## How to use
To use the FNSS Java library, you need to add the FNSS Jar file to the classpath of your project. The FNSS library is packaged in the file fnss-java.jar provided in the `dist` directory. All you have to do is to add this Jar file to your classpath. In addition to that, you need to have the [JDOM 2](http://www.jdom.org/) library on your classpath as well, which is used by FNSS to parse XML files. For your convenience, we provided the JDOM Jar file in the `lib` directory.
After adding FNSS and Jdom to your classpath, you can start using FNSS by importing the package `uk.ac.ucl.ee.fnss` in your code.
To learn how to use the library, you can either look at the Javadoc documentation in the `doc` subdirectory or look at some examples provided in the `examples` subdirectory.
Should you need any further information, please contact us and we'll be happy to help you.
 
## Requirements
* [Java Runtime Environment (JRE)](http://www.java.com/) (version 1.6 or later)
* [JDOM 2 library](http://www.jdom.org/). A copy of the library jar is located under the `lib` subdirectory

## License
The FNSS Java library is released under the terms of the  [BSD License](http://en.wikipedia.org/wiki/BSD_licenses). See LICENSE.txt.