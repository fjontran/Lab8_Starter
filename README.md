# Lab 8 - Starter
Jon Tran | A15793780
1. Within a Github action that runs whenever code is pushed. 
Having automated testing after you push your code onto Github is ideal so that you can build a version history which can act as a log. Having these tests in a Github action allows for your team to see what issues arise and to adjust their plans accordingly. If we ran all our tests locally, our team would not have the ability to look at the results and see where any potential bugs and issues are. Running them all after development is simply risky as if a huge bug is found, it can jeopardize the release of the software.
2. No. E2E testing emulates user actions such as clicking on buttons and more. It would be better to do earlier tests to see if each function works before involving user interactions with them. If we use E2E testing to test such things, then confounding variables may lead to a bug which would be hard to fix. 
