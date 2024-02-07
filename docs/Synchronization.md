---
title: Synchronization 
id: synchronization
---
# SonarQube 10.4 
SonarQube is a self-managed, automatic code review tool that systematically helps you deliver Clean Code. As a core element of our Sonar solution, SonarQube integrates into your existing workflow and detects issues in your code to help you perform continuous code inspections of your projects. The product analyses 30+ different programming languages and integrates into your Continuous Integration (CI) pipeline of DevOps platforms to ensure that your code meets high-quality standards.

## Writing clean code
Clean Code is the standard for all code that results in secure, reliable, and maintainable software therefore, writing clean code is essential to maintaining a healthy codebase. This applies to all code: source code, test code, infrastructure as code, glue code, scripts, and more. For details, see Clean Code.

Sonar's Clean as You Code approach eliminates many of the pitfalls that arise from reviewing code at a late stage in the development process. The Clean as You Code approach uses your quality gate to alert/inform you when there’s something to fix or review in your new code (code that has been added or changed), allowing you to maintain high standards and focus on code quality.

# Developing with Sonar

![Sonar](./image/sonarqube.png)
The Sonar Solution helps you define your code as fit for production.
The Sonar solution performs checks at every stage of the development process:

SonarLint provides immediate feedback in your IDE as you write code so you can find and fix issues before a commit.
SonarQube’s PR analysis fits into your CI/CD workflows with SonarQube’s PR analysis and use of quality gates.
Quality gates keep code with issues from being released to production, a key tool in helping you incorporate the Clean as You Code methodology.
The Clean as You Code approach helps you focus on submitting new, clean code for production, knowing that your existing code will be improved over time.
Learn more about the types of issues that SonarQube detects.

Organizations start off with a default set of rules and metrics called the Sonar way quality profile. This can be customized per project to satisfy different technical requirements. Issues raised in the analysis are compared against the conditions defined in the quality profile to establish your quality gate.

A quality gate is an indicator of code quality that can be configured to give a go/no-go signal on the current release-worthiness of the code. It indicates whether your code is clean and can move forward.

A passing (green) quality gate means the code meets your standard and is ready to be merged.
A failing (red) quality gate means there are issues to address.
SonarQube provides feedback through its UI, email, and in decorations on pull or merge requests (in commercial editions) to notify your team that there are issues to address. Feedback can also be obtained in SonarLint supported IDEs when running in connected mode. SonarQube also provides in-depth guidance on the issues telling you why each issue is a problem and how to fix it, adding a valuable layer of education for developers of all experience levels. Developers can then address issues effectively, so code is only promoted when the code is clean and passes the quality gate.

## Getting started
Now that you've heard about how SonarQube can help you write clean code, you are ready to try out SonarQube for yourself. You can run a local non-production instance of SonarQube and initial project analysis. Installing a local instance gets you up and running quickly, so you can experience SonarQube firsthand. Then, when you're ready to set up SonarQube in production, you'll need to install the server before configuring your first code analysis.

The Analyzing source code section explains how to set up all flavors of analysis, including how to analyze your project’s branches and pull requests.

More getting started resources
How to set up and upgrade
How to create and import projects
How to administer an instance
How to set up portfolios
