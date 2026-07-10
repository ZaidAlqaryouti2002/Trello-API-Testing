# Trello API Testing Project 🚀

A comprehensive API testing automation project using **Postman** to validate the core functionalities of the Trello REST API. 

This repository contains a structured Postman collection consisting of **18 specific API requests** designed to test the full lifecycle of Trello workspaces, including Boards, Lists, and Cards management.

## 🛠️ Tools & Technologies Used
* **API Testing Tool:** Postman
* **Scripting Language:** JavaScript (Postman Tests/Pre-request scripts)
* **Target API:** [Trello REST API](https://developer.atlassian.com/cloud/trello/rest/)
* **Version Control:** Git & GitHub

## 📋 Project Features
* **CRUD Operations:** Comprehensive coverage of Create, Read, Update, and Delete operations.
* **Workflow Automation:** End-to-end testing scenarios simulating real user interactions.
* **Environment Variables:** Dynamic variable extraction and usage (e.g., passing `board_id` and `list_id` to subsequent requests) to ensure seamless execution.
* **Automated Assertions:** Automated test scripts for validation, including:
  * HTTP Status Code verification (200 OK, 400 Bad Request, 404 Not Found, etc.)
  * Response Time checks
  * JSON Body validation and structure verification

## 🗂️ Test Suite Structure
The collection is organized into logical folders mirroring Trello's architecture:
1. **Board Management:** Creating new boards, retrieving board details, updating board settings, and deleting boards.
2. **List Management:** Creating lists within specific boards and fetching list data.
3. **Card Management:** Creating cards within lists, updating card descriptions, moving cards, and deleting cards.

## 🚀 How to Run the Tests

### Prerequisites
1. Install [Postman](https://www.postman.com/downloads/).
2. Create a [Trello Account](https://trello.com/).
3. Generate your Trello **API Key** and **API Token** from the [Trello Power-Up Admin portal](https://trello.com/app-key).

### Setup Instructions
-1 Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/ZaidAlqaryouti2002/Trello-API-Testing.git](https://github.com/ZaidAlqaryouti2002/Trello-API-Testing.git)
   
-2 Open Postman.

-3 Import the Trello APIs Collection.json file.

-4 Import the Trello API Environment.json file.

-5 In Postman, select the imported environment and update the Current Value for the following variables with your actual credentials:

-6 API_KEY: Your Trello API Key.

API_TOKEN: Your Trello API Token.

BASE_URL: https://api.trello.com/1

Execution
Manual Execution: Click on individual requests and hit Send.

Automated Execution: Open the Postman Collection Runner, configure the delay (if needed), and click Run Trello-API-Collection.

