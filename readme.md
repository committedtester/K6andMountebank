# K6 and Mountebank

As a quick POC I wanted to see how quick I could setup a repository that contained Mountebank for mocking and K6 for load testing. The goal being to mock out system behaviour for later validation under load


## To get started
npm run mock (to start mountebank on localhost)
npm run k6 (to then run k6 against localhost)