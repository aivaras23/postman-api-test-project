# Automated API Testing with Postman and Newman

## 1. What are we testing and what is this about?

This project focues on testing different functionalities of <a href="https://www.automationexercise.com/">Automation Exercise Website</a> API with Postman.

What test cases have been tested in this project?

-   API 1: Get All Products List
-   API 2: POST To All Products List
-   API 3: Get All Brands List
-   API 4: PUT To All Brands List
-   API 11: POST To Create/Register User Account
-   API 12: DELETE METHOD To Delete User Account
-   API 13: PUT METHOD To Update User Account
-   API 14: GET user account detail by email

## 2. Prerequisites

Before you begin, ensure you have the following installed on your machine:

-   Node.js
-   npm or yarn package manager
-   Postman

## 3. Set up

1. Clone the repository:

    ```bash
    git clone https://github.com/aivaras23/.git
    ```

2. Navigate into the project directory:

    ```bash
    cd
    ```

3. (Optional) If you're using Visual Studio Code, you can open the project directly in VS Code:

    ```bash
    code . -r
    ```

4. Open your terminal (or terminal in your code editor) and install the required dependencies:

    ```bash
    npm i
    ```

    Or, if you are using yarn:

    ```bash
    yarn
    ```

## 4. How to Run Tests

1. Once the dependencies are installed, you can run the Newman tests using the following command:

    ```bash
    npm run test
    ```

    Or, if using yarn:

    ```bash
    yarn test
    ```
