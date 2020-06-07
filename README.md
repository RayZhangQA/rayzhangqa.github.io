# This is the website of RayZ's Quality Assurance House


Repo for Selenium WebDriver Automation Project


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run the project locally, please make sure to have the following downloaded and installed (if applicable):

* [Java 8 JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) - any version of Java Standard Edition Development Kit 8
* [Eclipse](http://www.eclipse.org/downloads/eclipse-packages/) - any newer version of Eclipse IDE for Java EE Developers

### Setup

1. Download and install Java JDK
2. Download and extract Eclipse
3. Eclipse: Window >> Preferences >> Java >> Installed JREs >> select installed JREs >> Edit >> make sure that JRE Home points to C:\Program Files\Java\jdk1.8.0_xxx\jre directory
4. Eclipse: Help >> Eclipse Marketplace >> type testng in Find search box >> click install button for TestNG for Eclipse
5. Download and extract [QA Automation repo](https://github.com/ShawONEX/qa-automation)
6. Copy/Paste qa-automation\WebDriver folder to your Eclipse's workspace folder
7. Eclipse: File >> Import >> Existing Maven Projects >> Next >> Root Directory should be your Eclipse's workspace\WebDriver folder (for example: C:\Users\username\Desktop\workspace\WebDriver) >> Finish
8. Eclipse: Expand imported WebDriver project within the Eclipse's Package Explorer >> right mouse click on pom.xml file >> Run As >> Maven install

### Running the tests

1. To run individual test: Eclipse >> expand src/test/java within package explorer >> right mouse click any test (.java file) within any test package >> Run As >> TestNG Test
2. To run group of tests within the test suit: Eclipse >> expand resources within package explorer >> right mouse click any suite (.xml file) >> Run As >> TestNG Suite


### Documentation

More reading available [here](https://github.com/ShawONEX/qa-automation/tree/master/WebDriver/docs)


Arcana by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A business/corporate style responsive site template. It's pretty barebones but should
go over pretty well for folks wanting to get their serious business on.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = Not included)

Feedback, bug reports, and comments are not only welcome, but strongly encouraged :)

AJ
aj@lkn.io | @ajlkn

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)
