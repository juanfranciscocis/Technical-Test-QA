
You are working as a QA Engineer at a company that's building a new web application. One of the developers at the company has just finished work a registration form to enable new users to create accounts; he has moved the user story ticket into QA and assigned it to you. The ticket that you are assigned is as follows: 
<i> 
### Description: 
As a new user of the application, I want to be able to register an account with a username/email address and a password. I should be able to read the terms of the application before deciding to register, and I must accept said terms before I create my account. When I submit the form, I want to be presented with an alert that shows me whether my registration was a success or whether there are any issues. 

### Acceptance Criteria:
1. I need to enter either an email or username - the format of which does not currently matter to this ticket
2. I need to enter a password with a minimum character count of 6, and a maximum character count of 16
3. I must be prompted to re-enter my password, and the entered value must match the password
4. I must be able to view the terms and conditions before I submit the form
5. I need to accept the terms and conditions before I can register
6. When I click the register button, I am shown an alert. The content of the alert will depend on whether the form was completed in line with the acceptance criteria. If the form doesn't adhere to points 1-5 of the acceptance criteria, the alert message will suggest a failure, and the form will fail to submit. However, if the form is completed as per the acceptance criteria, the alert will a success message, and the form will be submitted. </i>
## Your Task: 

### Set-up (Not necessary):
1. Clone this repo and change the directory to the 'ui' folder
2. Run `npm i` to create the node_modules folder (you may need to [install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) for this step)
3. Run `npx live-server` to run the webpage locally and select _'html > form.html'_ 

### Step 2 - Produce test cases:
1. Produce a set of test cases that you'd use to test the registration form and its acceptance criteria 

*Note: There's no need to produce a set of formal test cases, just a simple draft*

### Step 3 - Execute the test cases:
1. Execute the test cases that you created in step 2 and note down any issues that you find
