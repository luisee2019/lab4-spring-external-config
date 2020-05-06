# Lab 4: Using Spring Boot and Externalizing Application Configuration

In this lab, you will learn how to create Spring Boot applications and externalize properties in your application.

## Getting Started

1. Create a private repository for this assignment by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#create-a-private-repository-for-completing-this-assignment) making the following substitutions:
    * For step 2, use this URL: [https://github.com/jeff-anderson-cscc/lab4-spring-external-config/generate](https://github.com/jeff-anderson-cscc/lab4-spring-external-config/generate) to create your private repository from my template
    * For step 3, name your repository: ``lab4-spring-external-config``
1. Add me as a collaborator so I can view and grade your work by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#add-me-as-a-collaborator-so-i-can-view-and-grade-your-work)
1. Create and checkout a new project for this lab in IntelliJ by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#create-and-checkout-a-new-project-for-this-lab-in-intellij)
1. **IMPORTANT:** Before you start coding, create a new branch for your work as [described here](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#important-before-you-start-coding)

## Completing the Assignment

**Important: You may not change the code in any test cases.** _For a passing grade, the only permissible difference between the base version of each JUnit test class and yours is yours will have no tests commented out and the file is otherwise identical._

### Instructions for completing the assignment:

1. In the ``pom.xml``, add the latest Spring Boot parent pom and
two dependencies: ``spring-boot-starter`` and ``spring-boot-starter-test``
1. Starting with ``edu.cscc.java4.sbootlab.SpringAppTests``:
    1. get the first test to pass
    1. One by one, get the next test to pass
1. Once SpringAppTests is completely working, repeat the steps above with ``edu.cscc.java4.sbootlab.SpringAppDevProfileTests``
1. Once you are done, commit your changes using "VCS" -> "Commit":
    * Make sure the commit includes any new files you created
    * Enter a proper comment
    * Uncheck "Perform code analysis"

### Hints from the documentation:

* [13.2.1 Inheriting the Starter Parent](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#using-boot-maven-parent-pom)
* [13.5 Starters](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#using-boot-starter)
* [18. Using the @SpringBootApplication Annotation](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#using-boot-using-springbootapplication-annotation)
* [24. Externalized Configuration](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#boot-features-external-config)
* [24.3 Application Property Files](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#boot-features-external-config-application-property-files)
* [24.4 Profile-specific Properties](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#boot-features-external-config-profile-specific-properties)
* [24.8 Type-safe Configuration Properties](https://docs.spring.io/spring-boot/docs/2.1.3.RELEASE/reference/htmlsingle/#boot-features-external-config-typesafe-configuration-properties)

## Submitting your work

1. Push your changes to GitHub, create a pull request, and ask for my review by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#push-your-changes-and-create-a-pull-request-for-grading)
1. Once I have reviewed and approved your pull request, follow [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#once-your-pull-request-is-reviewed-and-approved) to submit your assignment in Blackboard


