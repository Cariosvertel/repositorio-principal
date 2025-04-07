:: Description
:: (A brief and clear description of the change made, the purpose of the PR, and its impact on the project.)
:: Example:
:: This PR adds functionality to allow user registration via Google, improving the onboarding experience
:: by reducing friction during the sign-up process.

:: -----------------------------------------------------------------------------

:: Motivation
:: (Explain the reason behind the change and provide context. You can include related tickets or user feedback if relevant.)
:: Example:
:: This change addresses user requests for Google sign-up, based on a previous ticket.
:: Google authentication enhances accessibility and overall user experience.

:: -----------------------------------------------------------------------------

:: Screenshots
:: (Include images for visual or UI changes. Adding a "before and after" comparison can be helpful.)
:: Example:
:: Before the change:
:: ![Before](path/to/image1.png)
:: After the change:
:: ![After](path/to/image2.png)

:: -----------------------------------------------------------------------------

:: Pre-Submission Checklist
:: (All the following questions must be completed before submitting the PR.)

:: [ ] Is the code free of errors or unhandled exceptions?
::     - Ensure there are no unexpected errors that could affect application stability.
::     - Example: I tested the Google sign-up flow, and no errors occurred.

:: [ ] Have the necessary unit or integration tests been performed?
::     - Ensure that all relevant functionalities and cases are covered with tests.
::     - Example: I added unit tests for the Google authentication function.

:: [ ] Does the code follow project style guidelines and best practices?
::     - Check that the code is well-structured and adheres to the team's conventions.
::     - Example: I verified that all code follows the project's style guidelines.

:: [ ] Has it been tested on major browsers and devices?
::     - If it impacts the UI or frontend, ensure it works across major browsers.
::     - Example: I tested the sign-up form on Chrome, Firefox, and Safari, and it worked correctly in all.

:: [ ] Has application performance remained stable or improved?
::     - Ensure the change has not negatively impacted application performance.
::     - Example: The registration page loads at the same speed as before the change.

:: [ ] Have necessary dependencies been updated, if applicable?
::     - Make sure that external libraries or dependencies are updated or properly configured.
::     - Example: I updated the Google authentication library to the latest stable version.

:: [ ] Has the change been documented if necessary?
::     - If the change requires documentation updates, ensure they are made.
::     - Example: The documentation for Google authentication has been updated to reflect this change.

:: [ ] Are errors and user messages handled correctly?
::     - Ensure that any errors related to this feature are properly managed and clear to the user.
::     - Example: If authentication fails, the user receives a clear error message.

:: [ ] Does the change affect other functionalities that need testing?
::     - Consider if the change might have side effects on other parts of the application.
::     - Example: I tested that authentication changes did not affect other login methods, such as email sign-in.

:: -----------------------------------------------------------------------------

:: Type of Change
:: (Check all that apply. You can add other options as needed.)
:: [ ] New feature
:: [ ] Bug fix
:: [ ] Documentation update
:: [ ] Style improvement (UI/formatting changes)
:: [ ] Refactoring (code restructuring without changing behavior)
:: [ ] Performance optimization
:: [ ] Test updates

:: -----------------------------------------------------------------------------

:: How to Test
:: (Describe detailed steps to test the functionality effectively. Consider adding a checklist of specific tasks.)
:: Example:
:: 1. Clone the repository and switch to the PR branch.
:: 2. Open the user registration page.
:: 3. Click on "Sign up with Google."
:: 4. Verify that the authentication process works correctly.
:: 5. Ensure the user is redirected to the welcome page after registration.

:: -----------------------------------------------------------------------------

:: Additional Notes
:: (Any extra information reviewers may need, such as dependencies, configurations, or potential side effects.)
:: Example:
:: Google API credentials need to be configured in the settings file to test this change.
:: Make sure to have the correct credentials before testing.
