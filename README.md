### Project Overview
This repository contains a collection of test cases for a scooter delivery application, covering both the mobile and web app, as well as the backend API. The tests were designed to ensure the application's functionality, usability, and stability across various platforms and conditions. This project demonstrates a comprehensive approach to quality assurance, including:

* **Functional Testing:** Verifying that features work as intended.
* **Boundary Value Analysis and Equivalence Partitioning:** Rigorously testing input fields with valid and invalid data to ensure robust error handling.
* **User Interface (UI) Testing:** Comparing the application's visual elements against design composites to ensure a consistent user experience.
* **Negative Testing:** Validating how the application handles unexpected user actions or conditions, such as a lack of internet connectivity or invalid data.
* **API Testing:** Ensuring the backend endpoints behave correctly under different scenarios, including successful and failed requests.

### Test Case Breakdown
The test cases are organized into three main categories:

<img width="433" height="757" alt="Screenshot 2025-07-24 153903" src="https://github.com/user-attachments/assets/08b8fe5d-71ad-4c7d-9d2c-718bd906c9c7" />

**1. Mobile App Testing (`Mobile Test Cases.csv`)**

This section focuses on the mobile application for couriers. Key areas tested include:
* **Notifications:** Verifying the delivery of a 2-hour reminder notification, its content, and its behavior under various app states (active, minimized, screen off).
* **Internet Connectivity:** Testing the app's behavior when the internet connection is lost, including the display and dismissal of "No Internet connection" pop-ups.
* **Composites (UI) Matching:** Ensuring the app's interface (Login, All orders, My orders screens) aligns with the Figma design composites.

<img width="1564" height="776" alt="Screenshot 2025-07-21 131732" src="https://github.com/user-attachments/assets/a2146931-db06-4526-bd42-18cc775070d5" />

**2. Web App Testing (`Web App Test Cases.csv`)**

These test cases evaluate the web application on different browsers (Chrome and Opera).
* **General Requirements:** Verifying that core pages (Landing and Order pages) match the design composites.
* **Form Field Validation:** Extensive testing of the "First Name," "Last Name," "Address," and "Phone" input fields using boundary value analysis and equivalence class partitioning to ensure proper data validation and error messaging.

**3. Backend API Testing (`Backend Test Cases.csv`)**
This section focuses on the backend API for courier management.
* **Courier Deletion Endpoint (`DELETE /api/v1/courier/:id`):** Testing the deletion of courier accounts under different conditions, including couriers with and without linked orders, non-existent IDs, and invalid ID formats.

### Key Skills Demonstrated

* **Test Case Design:** Creating clear, detailed, and organized test cases with preconditions, steps, expected results, and test data.
* **Bug Reporting:** Identifying and documenting bugs with links to a bug-tracking system (Jira), including details like actual results and failure status.
* **Test Strategy:** Employing various testing techniques like positive, negative, boundary value, and equivalence class testing.
* **Cross-Platform Testing:** Executing tests across different environments (mobile emulator, web browsers like Chrome and Opera) and operating systems (Windows 10, Android).
* **Attention to Detail:** Meticulously comparing UI elements to design specifications and verifying precise notification content and error messages.

### How to Navigate This Repository
* **`Mobile Test Cases - Test Cases.csv`**: Contains test cases for the Android mobile application.
* **`Web App Test Cases - Test Cases.csv`**: Specific test cases for the web app when tested on Google Chrome.
* **`Backend Test Cases - Test Cases.csv`**: API test cases for the courier management backend.

Feel free to explore the files to see examples of my work in action.
