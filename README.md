# The fundamentals of CI/CD 


The fundamentals of CI/CD which is short for Continuous Integration/Continuous Delivery and be able to apply these fundamentals in our iOS app development process.

The word Deployment is often used in place of Delivery but effectively means the same thing.

What is Continuous Integration (CI) ?

CI is the practice of merging all programmers current working copies to a shared mainline on a regular basis (usually several times a day).

A developer checks out a working copy of the code base prior to making a change.  Over time as other developers check out and make changes, this checked out working copy of the source code base gets out of date, potentially requiring more and more work by developers to actually  check their completed changes back in to the main repository.

Without using CI it can become really difficult to merge all these changes and can lead to it taking more time to  merge changes back into the main source code base than it took to make the the change itself.

CI seeks to eliminate this problem by making sure all developers integrate early and often with the goal to reduce rework and ultimately save cost and time.  This involves all developers merging their code back into the main repository multiple times a day.

An added bonus is that each programmer who is merging changes needs to build and run (and pass) all unit tests which usually run automatically meaning the code base is easier to work with and merge changes into and is potentially more stable as a result.

What is Continuous Delivery or Deployment (CD) ?

This extends CI to ensure that new changes to software can be released to clients quicker, but in a more sustainable way.  It takes the advantages of CI from a development perspective (automated testing, on code check-in, etc) allowing the actual code base to be built and new releases to be automatically released to the client, effectively meaning a new version can be deployed to the client by a click of a button.

CI/CD concepts.

By adhering to a CI/CD development process, the code base can be built and released more quickly, and is in a more stable state overall.  

Key topics in this Repo.

1. Continuous Integration

2. Continuous Delivery

3. App Center

4. GitHub Pull Requests

5. Branch protection

6. UI Tests

7. App Diagnostics

8. App Analytics



• how to track errors and crashes in your apps.

• how to track any event triggered within your apps.

• Apply complete CI/CD flows in app development process.

• Use GitHub to trigger code checks and app distribution to users.

• Use App Center to automate checks and protect important branches.

• Leverage App Center to automatically create builds on every merge.

• Automate the distribution of a new build to beta testers.

• Automate the distribution of new releases to the Google app store.

• Focus on the development of features, leave the build and distribution to App Center.

• Improve teamwork with automatic builds and checks that improve the quality of your merges.

• Enable product discovery with the help of Analytics in the App Center.

• Test app in a wide array of cloud-hosted physical devices.

Dev: ![Build status](https://build.appcenter.ms/v0.1/apps/353c188c-ab38-463e-8dca-1a0bbb368b68/branches/Dev/badge)

Test: [![Build status](https://build.appcenter.ms/v0.1/apps/f955fdf6-5f67-4abf-8ed1-1feb8a1a9b0c/branches/Test/badge)](https://appcenter.ms)

Master: [![Build status](https://build.appcenter.ms/v0.1/apps/f955fdf6-5f67-4abf-8ed1-1feb8a1a9b0c/branches/main/badge)](https://appcenter.ms)
