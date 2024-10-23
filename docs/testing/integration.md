# Integration Testing

**Purpose**: Verify that combined components or systems interact correctly and function together as intended.  

**Tools**:

  - **Postman**: API testing tool for sending requests and validating responses.
  - **SoapUI**: Tool for testing SOAP and REST APIs.
  - **JUnit/TestNG**: Can also be used for integration testing in Java.
  - **Moq**: A .NET mocking framework for simulating components.  

**Types**:

  - **Big Bang Testing**: All components are integrated at once and tested together.
  - **Incremental Testing**: Components are integrated and tested step-by-step.
    - **Top-Down Integration Testing**
    - **Bottom-Up Integration Testing**

These are performed on the CI Server.
