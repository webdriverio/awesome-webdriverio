<h3 align="center">
	<img width="355" src="https://raw.githubusercontent.com/webdriverio/awesome-webdriverio/main/.github/workflows/assets/awesome_webdriverio_branding.png" alt="awesome-webdriverio">
	<br>
</h3>

**[WebdriverIO](https://github.com/webdriverio/webdriverio)** Next-gen browser and mobile automation test framework for Node.js

# Awesome WebdriverIO [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Test](https://github.com/webdriverio/awesome-webdriverio/actions/workflows/test.yaml/badge.svg)](https://github.com/webdriverio/awesome-webdriverio/actions/workflows/test.yaml)

**A curated list of awesome WebdriverIO resources, libraries, tools and applications**

Inspired by the [awesome](https://awesome.re) list. Feel free to improve this list by [contributing](https://github.com/webdriverio/awesome-webdriverio/blob/master/contributing.md)!

<!--lint disable list-item-indent-->

## Contents

- [WebdriverIO Ecosystem](#webdriverio-ecosystem)
  - [Support WebdriverIO](#support-webdriverio)
  - [Documentation](#documentation)
  - [Community](#community)
  - [Twitter](#twitter)
- [Plugins](#plugins)
  - [Services](#services)
  - [Reporters](#reporters)
  - [Miscellaneous](#miscellaneous)
- [Research & Training](#research--training)
  - [Articles](#articles)
  - [Videos](#videos)
  - [Conference/Meetup Talks/Webinars](#conferencemeetup-talkswebinars)
  - [Courses](#courses)
  - [Books](#books)
  - [WebdriverIO Examples](#webdriverio-examples)

<!--lint disable list-item-indent-->

## WebdriverIO Ecosystem

### Support WebdriverIO

- [WebdriverIO Open Collective](https://opencollective.com/webdriverio) - Help support the teams ongoing development efforts.

### Documentation

- [WebdriverIO 4.x](http://v4.webdriver.io) - WebdriverIO 4.x Documentation.
- [WebdriverIO 5.x](http://v5.webdriver.io) - WebdriverIO 5.x Documentation.
- [WebdriverIO 6.x](http://v6.webdriver.io) - WebdriverIO 6.x Documentation.

### Community

- [Stack Overflow](http://stackoverflow.com/tags/webdriver-io)
- [Gitter Chat](https://gitter.im/webdriverio/webdriverio)
- [#webdriverio in Selenium Slack](https://seleniumhq.slack.com/join/shared_invite/zt-f7jwg1n7-RVw4v4sMA7Zjufira_~EVw)

### Twitter

*People passionate about WebdriverIO (In no particular order)*

- [Christian Bromann](https://twitter.com/bromann) - Staff Software Engineer at the Open Source Program Office at Sauce Labs.
- [Kevin Lamping](https://twitter.com/klamping) - Senior Front End Engineer.
- [Wim Selles](https://twitter.com/wswebcreation) - Senior Solutions Architect at Sauce Labs.

## Plugins

### Services

- [WebdriverIO Community Services](https://github.com/webdriverio-community?q=service) - A set of community maintained services.
- [Wdi5](https://github.com/js-soft/wdi5) - Cross-platform test framework for hybrid UI5 apps. wdi5 = Webdriver.IO + UI5 Test API + appium.
- [ChromeDriver](https://github.com/webdriverio-community/wdio-chromedriver-service) - Run Chrome browser seamlessly when running tests.
- [SafariDriver](https://github.com/webdriverio-community/wdio-safaridriver-service) - Run Safari browser seamlessly when running tests.
- [GeckoDriver](https://github.com/webdriverio-community/wdio-geckodriver-service) - Run Gecko browser seamlessly when running tests.
- [EdgeDriver](https://github.com/webdriverio-community/wdio-edgedriver-service) - Run Microsoft Edge browser seamlessly when running tests.
- [Gmail](https://github.com/webdriverio-community/wdio-gmail-service) - Fetch e-mails from Google Mail.
- [Intercept](https://github.com/webdriverio-community/wdio-intercept-service) - Capture and assert HTTP ajax calls.
- [Zafira Listener](https://github.com/shashidharus/wdio-zafira-listener-service) - Report tests to Zafira Dashboard.
- [Report Portal](https://github.com/borisosipov/wdio-reportportal-service) - Service used by Report Portal Reporter.
- [Docker](https://github.com/stsvilik/wdio-docker-service) - Helps run functional/integration tests against/using containerized applications.
- [WireMock](https://github.com/erwinheitzman/wdio-wiremock-service) - Run WireMock seamlessly when running tests.
- [Slack](https://github.com/carmenmitru/wdio-slack-service) - Send test results as a slack notification/message to channels.
- [LambdaTest](https://github.com/LambdaTest/wdio-lambdatest-service) - Manage tunnel and job metadata for LambdaTest users.
- [Image Comparison (Visual Regression Testing)](https://github.com/wswebcreation/wdio-image-comparison-service) - Image comparison and visual regression testing.
- [Ng-apimock](https://github.com/ng-apimock/webdriverio-plugin) - Service used by @ng-apimock/core.
- [Novus Visual Regression](https://github.com/Jnegrier/wdio-novus-visual-regression-service) - Visual regression testing.
- [Re-run](https://github.com/jwplayer/wdio-rerun-service) - Tracks failing tests and scenarios, allowing failing or unstable tests or scenarios to be re-run.
- [winappdriver](https://github.com/licanhua/wdio-winappdriver-service) - Run WinAppDriver server seamlessly when running tests.
- [ywinappdriver](https://github.com/licanhua/wdio-ywinappdriver-service) - Run ywinappdriver server seamlessly when running tests.
- [PerformanceTotal](https://github.com/tzurp/performance-total) - Analyze performance of test automated flows.
- [CleanupTotal](https://github.com/tzurp/cleanup-total) - Proper cleanup after each test made easy.
- [AWS Device Farm](https://github.com/awslabs/wdio-aws-device-farm-service) - AWS Device Farm service.
- [OCR service for Appium Native Apps](https://github.com/wswebcreation/wdio-ocr-service) - Run Tesseract OCR for Appium Native App tests.
- [Auto-detect missing imports w/eslint](https://github.com/jamesmortensen/wdio-eslinter-service) - Automatically run eslint checks prior to executing tests.

### Reporters

- [WebdriverIO Community Reporters](https://github.com/webdriverio-community?q=reporter) - A set of community maintained reporters.
- [Report Portal](https://github.com/borisosipov/wdio-reportportal-reporter) - Report results to Report Portal.
- [Video](https://github.com/presidenten/wdio-video-reporter) - Makes videos of failed tests and has optional allure integration.
- [HTML](https://github.com/rpii/wdio-html-reporter) - Generates a nice HTML report.
- [JSON](https://github.com/fijijavis/wdio-json-reporter) - Report results in JSON format.
- [Mochawesome](https://github.com/fijijavis/wdio-mochawesome-reporter) - Report results in Mochawesome format.
- [Timeline](https://github.com/QualityOps/wdio-timeline-reporter) - Report results in an aggregated visualisation interface.
- [CucumberJS](https://github.com/wswebcreation/wdio-cucumberjs-json-reporter) - Report results in CucumberJS JSON format.
- [Markdown](https://github.com/carmenmitru/wdio-markdown-reporter) - Report results in Markdown format.
- [Delta Reporter](https://github.com/delta-reporter/delta-reporter-wdio) - Report results in Delta Reporter format.
- [Teamcity](https://github.com/webdriverio-community/wdio-teamcity-reporter) - Report results to the build results page of Teamcity Portal.

### Miscellaneous

- [wdio-wait-for](https://github.com/webdriverio-community/wdio-wait-for) - A lightweight library of useful expected conditions for the WebdriverIO framework.
- [@wdio/schematics](https://github.com/webdriverio/webdriverio-schematics) - A schematic to add WebdriverIO to an Angular project.
- [@badisi/wdio-harness](https://github.com/Badisi/wdio-harness) - WebdriverIO support for Angular component test harnesses.

## Research & Training

### Articles

- Ross Addinall | 20-Apr-21 - [Cypress vs WebDriverIO](https://vitaq.io/2021/04/20/cypress-vs-webdriverio).

### Videos

- [UI Automation with WebdriverIO](https://testautomationu.applitools.com/webdriverio-tutorial) - By Julia Pottinger.
- [Automated Software Testing with WebdriverIO](https://www.udemy.com/course/automated-software-testing-with-webdriverio/) - By Kaniel Outis.
- [WebdriverIO - Tutorial for beginners](https://www.youtube.com/watch?v=e8goAKb6CC0&list=PL6AdzyjjD5HBbt9amjf3wIVMaobb28ZYN) - By Automation Bro.
- [Learn WebdriverIO Course](https://www.youtube.com/watch?v=I5hRcPH5dx8&list=PL0y7qCn3hjLY6JvohBcmUHKHf_iOi8WuF&ab_channel=Front-endTestingwithKevin) - By Kevin Lamping.
- [WebDriverIO - JavaScript Tool](https://www.youtube.com/watch?v=7J3FnyEGXd4&list=PLFGoYjJG_fqqswF8qDdWNG3b-BtZfiqQn&ab_channel=NaveenAutomationLabs) - By Naveen AutomationLabs.
- [WebdriverIO : NETWORK LOGS](https://www.youtube.com/watch?v=Be9IPyxHmLs) - By Seventeenth Sep.
- [WebdriverIO with TypeScript and BDD Framework](https://www.youtube.com/watch?v=FnC--5WB8ow&list=PLGk7ftfMz7jbZcArQU894rAfo6B1PbXbG&ab_channel=TestAutomationHub) - By TestAutomationHub.

### Conference/Meetup Talks/Webinars

- [My favourite features of WebdriverIO](https://www.youtube.com/watch?v=CHcjEI3YZ7Y) - By Julia Pottinger.
- [The Nuts and Bolts of WebdriverIO](https://www.youtube.com/watch?v=jOmvPpzLMf8) - By Christian Bromann.
- [Using WebdriverIO with Data Provider](https://www.youtube.com/watch?v=0YQCVJk8K_Q) - By Kumar Vikram.
- [Scale Your Automated Testing with BrowserStack and WebdriverIO](https://www.youtube.com/watch?v=bW3SM46xslE) - By Kevin Lamping.
- [WebdriverIO - Bootstrap your test suite in mins](https://www.youtube.com/watch?v=a7tdIkTeM0o) - By Shweta Varma.

### Courses

- [Web App Testing with WebdriverIO](https://learn.webdriver.io) - By Kevin Lamping.

### Books

- [The Web App Testing Guidebook](https://leanpub.com/webapp-testing-guidebook) - Covers everything you need to know to get off the ground with UI testing. Examples are built using real-world scenarios, showing how you would actually write your tests. It's a step-by-step guide on how to effectively write UI test automation for the real world.
- [Practical WebDriverIO](https://www.springer.com/de/book/9781484266601) - Teaches you intermediate and advanced methods for using WebDriverIO APIs.

### WebdriverIO Examples

- [Boilerplate Projects](https://webdriver.io/docs/boilerplates) - Over time, our community has developed several projects that you can use as inspiration to set up your own test suite.

[Back to top](#contents)
