CI/CD development
#Jenkins&WildFly

This is a simple JSP Hello World CI/CD developement.

Eclipse to create a Dynamic Web Project integrated with Git, this upload the whole Project to github.com

Jenkins with pipeline that uses Git to get the Project, where there are two build phases:

2.1. The first one uses Apache mvn clean & install and,

2.2. The second one deploys the .war to WildFly.
