Linting of Java code can be done with tools such as Checkstyle and Sonarlint. There are also IDE integrations available.  

There are a lot of testing frameworks but JUnit is probably the most dominant unit testing framework for Java development. Other options include e.g TestNG, Mockito, JBehave and Selenium, depending on the type of testing (unit testing, integration testing, UI testing, automation).  

Typical build tools for Java are eg. Apache Maven, Ant with ivy, Graddle and SBT.
There are a lot of alternatives for the CI set-up of a Java project. These include for example: Buddy, TeamCity, Bamboo CI, Codeship, Travis CI, CircleCI, Buildkite and Shippable. Some of the mentioned CI tools like e.g. Travis are cloud-based only and others like CircleCI can be either cloud-based or self-hosted.  

I think the main factors to consider regarding the project's CI set-up are mainly resources and cost related:
- Project resources:
    - What is the size of the project and which resources are available?
    - Does the project have funding for maintaining their own CI server? 
- Human resources:
    - Does the project have people with the necessary skills for configuring and maintaining a self-hosted CI solution? This relates to the previous point, since dedicated people is also a cost issue.
- Pricing:
    - Should the CI tool be free to use or can the project afford paying a corporate licence/recurring fee?
