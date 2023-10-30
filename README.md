# ECE444-F2023-Lab5

## Link to Test Case

Added a test case to verify that there is a connection to access the User_Table in the database: https://github.com/ECE444-2023Fall/project-1-web-application-design-group19-webcrafters/blob/4d620b99ace48da92c0346786b68fdb59d5fb4c3/tests/betula_test.py#L174C1-L187C1

## What are the pros and cons of TDD?

### Pros
TDD is a useful practice in order to ensure that the code is fully functional and that all components integrate with each other smoothly. TDD is also great when working on large scale projects to avoid conflicts and issues when branches are merged into the main branch as all branches are tested to ensure that they build properly and pass all test cases. Hence, the production code won't be negatively affected by incoming new features. All the features will nicely integrate into the application.

### Cons
The negative side of implementing the TDD practice is that testing can be overdone. Furthermore, the checks on gits will take longer to pass as git now has to check that all test cases pass. Hence, the main downside of TDD is that implementing this practice just adds one more step to the development process of our project, but TDD is very crucial and should be implemented with limitations to ensure that it does not slow down our development process and ensures the smooth integration of all features into our web app.
