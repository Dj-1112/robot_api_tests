# Robot Framework API Testing with robotframework-requests

This project utilizes Robot Framework along with the `robotframework-requests` library for testing API requests. It is intended to be integrated with Jenkins for continuous testing.


## Installation

To install the necessary dependencies, run the following command:

```bash
  pip install robotframework-requests
```
    
## Running Tests

1. Navigate to the project directory in your terminal.
2. Run the desired test suite using the robot command followed by the path to the test file.
```bash
  robot tests/api_tests.robot
```
This will execute the specified test suite and display the results in the terminal.
## Test Suites

`api_tests.robot`: This file contains test cases for API requests. It verifies the functionality and responses of various API endpoints.
## Writing Test Cases

- Test cases are written in Robot Framework's plain text format, making them easy to read and understand.
- Utilize the keywords provided by the robotframework-requests library to interact with API endpoints.
- Maintain clear and descriptive test case names and documentation for better understanding.
## Test Data

Test data such as endpoint URLs, request payloads, and expected responses should be stored in variables for easier maintenance and reuse.
## Continuous Integration with Jenkins

Integrate the test suite into your Jenkins pipeline for continuous testing:

1. Configure a Jenkins job for your project.
2. Add a build step to execute the test suite using the robot command.
3. Schedule the job to run at regular intervals or trigger it automatically on code changes.
## Additional Resources

- [Robot Framework Documentation](https://robotframework.org/)
- [robotframework-requests Documentation](https://github.com/bulkan/robotframework-requests)

Happy testing!