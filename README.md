# Technical Test Assignment for QA Engineer - Product Integrity Position

Our team at Buddy has been looking to onboard a new QA team member in a Hybrid Role, and we're happy to see that you've made it this far.
The technical test is an important part of our assessment.

You are allowed to use the same tools you use for work, as we want to assess in a real-world scenario 

### Backend Task
You are tasked with developing test cases and automated tests for a JavaScript function responsible for calculating an employee's total weekly pay, taking into account both regular and overtime hours worked. The function’s specifications are as follows:

- **Functionality to Test:**
    - Regular hours are paid at the normal rate.
    - Overtime hours, defined as hours worked beyond 40 in a week, are paid at 1.5 times the regular rate.
    - The function should accept three parameters:
        1. `regularHours`: The number of regular hours worked in the week.
        2. `overtimeHours`: The number of overtime hours worked in the week.
        3. `hourlyRate`: The hourly rate for the employee.

- **Your Goals:**
    1. **Identify Test Scenarios:** Determine a comprehensive set of scenarios that need to be tested. Consider normal cases, edge cases, and error-handling scenarios.
    2. **Write Detailed Test Cases:** For each scenario you identify, write a detailed test case that includes:
        - Test Case ID
        - Description
        - Pre-conditions
        - Steps to Execute
        - Expected Result
        - Post-conditions
    3. **Implement Automated Tests:** Using your chosen JavaScript testing framework (e.g., Jest or Mocha), write automated tests that cover the scenarios and test cases you have outlined. Your tests should programmatically assert the correctness of the payroll calculation function according to the specified behavior.

#### Deliverables
1. **Test Case Document:**
    - A document (PDF or Word format) containing all the test scenarios and detailed test cases you have developed. This document should clearly articulate the rationale behind each test case and its importance in ensuring the function's accuracy and robustness.

2. **Automated Test Code:**
    - Source code files for your automated tests. Please include a README file with:
        - Instructions on how to set up and run your tests.
        - Any necessary information about dependencies or environment setup.
    - Ensure your code is well-commented and organized to facilitate easy review.

3. **Submission Instructions:**
    - Bundle your test case document and source code (including the README file) into a single compressed file (ZIP format).
    - Submit your completed assignment via the email provided by our recruitment team.

#### Evaluation Criteria
Your submission will be evaluated based on the following criteria:
- **Comprehensiveness and Coverage:** Ability to identify a wide range of relevant test scenarios, including edge and error cases.
- **Clarity and Detail in Test Cases:** Precision and detail in the documentation of test cases, reflecting thoughtful consideration of the function's potential issues.
- **Quality of Automated Tests:** Effectiveness of your automated tests in covering identified scenarios, code quality, and the use of best practices in testing.
- **Documentation and Organization:** Clear, concise documentation (in code comments and README), and logical organization of your test cases and code.

#### Notes
- You are not required to implement the payroll calculation function itself; focus on the test cases and automated tests.
- If you have any questions or need further clarification about the assignment, please don't hesitate to contact our recruitment team.

We look forward to reviewing your submission and gaining insight into your approach to quality assurance and testing. Best of luck!

### Frontend Task
Your task is to develop test cases and automated tests for a web-based “Event Registration Form” used in a conference management application. 
This form includes several fields and functionalities, each with specific behaviors and requirements:
- **Functionality to Test:**
  1. **Form Fields:**
    - Name (text input)
    - Email (text input)
    - Registration Type (dropdown with options “Attendee”, “Speaker”, “Sponsor”)
    - Number of Tickets (numeric stepper input; visible only when “Attendee” is selected)
    - Presentation Topic (text input; mandatory and visible only when “Speaker” is selected)
    - Agree to Terms and Conditions (checkbox)
    - Submit Button
  2. **Expected Behaviors:**
    - All fields are required unless specified.
    - The form dynamically adjusts to show/hide fields based on the Registration Type selected.
    - The form validates input formats (e.g., Email format).
    - Upon submission, if any validation fails, appropriate error messages should be displayed.
    - A successful submission displays a confirmation message with the details entered.
- **Your Goals:**
  1. **Identify Test Scenarios:** Outline a comprehensive set of test scenarios, including user interactions, form validations, dynamic behavior based on inputs, and both successful and error states.
  2. **Write Detailed Test Cases:** Develop detailed test cases for each scenario identified, specifying:
    - Test Case ID
    - Description
    - Pre-conditions
    - Steps to Execute
    - Expected Result
    - Post-conditions
  3. **Implement Automated Tests:** Utilize a JavaScript-based testing framework suitable for UI testing (e.g., Cypress, Selenium WebDriver with JavaScript bindings) to write automated tests covering the scenarios and test cases you have outlined.
#### Deliverables
1. **Test Case Document:**
  - Document containing the test scenarios and detailed test cases, clearly describing the purpose and expected outcome of each.
2. **Automated Test Code:**
  - Source code for your automated tests, including a README with setup and execution instructions. Ensure your tests are well-commented to explain their purpose and logic.
3.  **Documentation of Expected Failures:**
  - Any observations or notes about test cases that are expected to fail and why, highlighting understanding of potential UI issues or areas for improvement.
4. **Submission Instructions:**
  - Combine your test case document and source code files (including the README) into a single ZIP file.
  - Submit your package to our team.
#### Evaluation Criteria
- **Comprehensiveness of Test Scenarios:** Coverage of various functional and non-functional aspects of the form, including edge cases.
- **Detail and Clarity of Test Cases:** The thoroughness and clarity in the documentation of test cases, highlighting your attention to detail and understanding of potential user interactions.
- **Quality and Effectiveness of Automated Tests:** Your automated tests’ ability to accurately and efficiently validate the UI’s behavior, code quality, and adherence to testing best practices.
- **Documentation and Organization:** The organization of your submission and the clarity of your documentation in both the test cases and code comments/README.
#### Additional Notes
- This assignment does not require you to implement the Event Registration Form itself; your focus should be on testing scenarios and automation.
- Feel free to ask any clarifying questions by reaching out to our recruitment team.
  We’re excited to see your approach to ensuring a flawless user experience through meticulous testing. Good luck with your assignment!

### Instructions for Candidates
- **Objective:** Write automated tests for the Event Registration Form provided in the `index.html` file. Focus on creating tests that interact with the form fields, simulate user inputs, and verify the dynamic behavior and validations of the form.
- **Test Scenarios to Consider:**
  - Form field visibility and requirements change based on the Registration Type selected.
  - Validation messages appear for missing required inputs upon form submission.
  - Successful form submission with all required fields filled correctly.
  - Incorrect email format validation.
  - Conditional fields (Number of Tickets, Presentation Topic) are properly validated when visible.
