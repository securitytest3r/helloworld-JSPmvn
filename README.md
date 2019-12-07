# CI/CD development
#Jenkins&WildFly

This is a simple JSP Hello World CI/CD developement.

Eclipse to create a Dynamic Web Project integrated with Git, this upload the whole Project to github.com

Jenkins with pipeline that uses Git to get the Project, where there are one build phase, and one post-build phase, respectively:

2.1. The first one uses Apache Maven clean & install and,

2.2. The second one deploys the .war to WildFly.

The file pom.xml contains the Project Object Model (POM) for this project that was used whit Maven.
