# Interactive Survey Tool API Tests

## Overview

This repository contains the Postman collection for testing the back-end API of the Interactive Survey Tool. This project is part of the AkademijaIT program and aims to ensure the functionality and reliability of the survey management system.

## Prerequisites

- **Interactive Survey Tool Backend**: Ensure you have access to the Interactive Survey Tool backend and have it running locally. The backend code is not publicly available.
- [Postman](https://www.postman.com/downloads/)
- [Newman](https://www.npmjs.com/package/newman) (optional, for running tests from the command line)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. **Import the Postman collection:**

Open Postman and import the Apklausų valdymo įrankis API.postman_collection.json file.

## Running Tests

**Using Postman**
1. Open Postman.
2. Import the collection file Apklausų valdymo įrankis API.postman_collection.json.
3. Ensure your Interactive Survey Tool backend is running.
4. Run the collection using the Postman interface.

**Using Newman**
1. Make sure you have Newman installed. If not, install it using npm:

```bash
npm install -g newman
```

2. Run the collection using Newman:

```bash
newman run Apklausų valdymo įrankis API.postman_collection.json
```

## Collection Structure

The collection is structured to cover various aspects of the Interactive Survey Tool's API, including:

- User Information
- Role Management
- Survey Information
- Survey Creation
- Survey Updating
- Respondent Management
- Survey State Management
- Answer Submission
- Embeddable Surveys
- Survey Answers Retrieval
- Survey Deletion
Each folder in the collection corresponds to a specific functionality and contains requests with pre-configured tests to validate the API responses.

## Test Results

An example test run can be found in the newman folder, which includes detailed reports of the API tests. Below is a summary of the test results:

- Total Requests: 358
- Total Assertions: 1596
- Failed Tests: 52
- Skipped Tests: 0
- Total Run Duration: 1m 9.1s
- Average Response Time: 104ms
