# SpringIntelliJTest
Spring MVC starter files for Intellij Idea Users 

You need two tool

1-Intellij Idea Ultimate

2-Tomcat Server Installed

1-Click New Project

2-Choose Maven and click Create from archetype

and make sure you choose org.apache.maven.archetypes:maven-archetype-webapp before say next

3-Then you can just click finish.

In the new project you need to do some configurations.

1) pom.xml

between the <dependencies></dependencies> tag you need to copy-paste that

    <dependency>
      <groupId>org.springframework</groupId>
      <artifactId>spring-webmvc</artifactId>
      <version>5.2.9.RELEASE</version>
    </dependency>
  </dependencies>
  

2)I just pushed to github my all directory but you don't need all of them 

just copy /src/main and paste your under directory /src/

3)Before you start run/edit configurations -> click + -> Select Tomcat Server -> Local

Then you will see tomcat server interface.

Server Tab-> Application server: show the Tomcat installed directory  and say ok.

Now you can run it!


