This is a Spring 3.2 MongoDB archetype based off the jestrange's spring-3.2-javaconfig-archetype

sprongo
===============================

Spring MongoDB JavaConfig Maven Archetype

Clone the repository containing the archetype:
==============================
git clone https://github.com/daquino/sprongo.git

Install the archetype:
==============================
mvn clean install

Run the archetype:
==============================
mvn archetype:generate -DarchetypeGroupId=com.refactify -DarchetypeArtifactId=sprongo -DarchetypeVersion=1.0 -DgroupId=your.package -DartifactId=yourappname

Run the application:
==============================
mvn clean tomcat7:run
