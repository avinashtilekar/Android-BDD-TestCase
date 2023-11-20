# Android-BDD-TestCase
This sample app is created for Android BDD (Behavior-Driven Development) test case with help of **Cucumber** & **Espresso**.

In Android world, the Espresso tests are the fastest thing ever, when we talk about UI Instrumentation tests. Espresso help to synchronising the test framework with the queue of GUI events that have to be processed by the system.

**Why recommending Espresso?**
1) It is a native testing framework, designed specifically for Android native app instrumentation tests.
2) It has perfect synchronisation between the tests and the IDLE (UI thread) of the Android platform.
3) It has significantly faster execution time than Appium, Calabash or any other testing frameworks for Android.
4) The Espresso framework would be placed alongside the app codebase, in the same repository like the source code and thus providing much easier navigation between the tests and the source code of the app.
5) Most android developers understand the Espresso testing framework just because it is part of their development kit.

**Why adding Cucumber in our UI tests?**
1) It runs automated acceptance tests written in BDD.
2) It works well with Espresso Framework;
3) It supports huge number of programming languages and most importantly — all JVM languages.
4) It enables anyone to write plain-text descriptions of the desired behaviour in any spoken language and runs automated tests. The latter being possible thanks to its plain language parser called **Gherkin**, that allows expected software behaviours to be specified in a logical language, understandable for all customers, stakeholders, managers, developers, QAs etc.
5) It provides you with the best documentation about your app.

**Install Gherkin plugin**

In Android Studio we need to install Gherkin plugin. This plugin provides Gherkin language support. Gherkin is the language that Cucumber uses to define test cases (test scenarios). It has been designed to be non-technical and human readable, collectively describing use cases relating to a software system. In a proper software development environment, these use cases would come from the acceptance criterias in the development tickets.

How to install Gherkin?

(Windows) Android studio >> File >> Settings >> Plugings >> Gherkin (Search in market) >> tap on Install

(Mac) Android studio >> File >> Settings >> Plugings >> Gherkin >> tap on Install

**Once the Gherkin plugin installation has been completed, you should proceed by restarting your Android studio.**

**Create .feature files**

create .feature files, where you shall describe your feature tests and test scenarios, you need to teach AS how to create these files. In Android studio, just right click on some of the code directories (for example androidTest) and select New -> Edit File Templates
