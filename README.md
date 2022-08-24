# BGSolutionsTestTask

The task was:
1. Go to the https://www.olympia.casino/
2. Open sign-up modal
3. Open any temp mail website (like https://tempmail.dev/en) in a separate tab
4. Copy the email address from step 3
5. Fill in the email in a modal from step 2
6. Generate random password and fill password field
7. Choose Aud currency
8. Find the Next button by TEXT (required and important step)
9. Click Next
10. Fill all other fields, continue to click next, and stop at the last step (before submitting).

As in Cypress is no option to switch between tabs, for this task I generated random data for fills 
if there is a need to connect "email check" in the future, there are plenty of services for that) 

# Get Started
To run a test with UI:
1. install all dependencies by running "npn install" in a folder with the repository
2. put "npx cypress open" (without quotation marks) at the terminal and press Enter
3. select e2e testing 
4. select a browser which you prefer or is installed on your OS 
5. select "sign_up_form"

To run the test without UI:
1. install all dependencies by running "npn install" in the folder with the repository
2. put "npx cypress run" (without quotation marks) at the terminal 
3. after a couple of minutes you will see the result of the run
