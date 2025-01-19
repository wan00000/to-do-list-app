
# To-Do List App

This repository demostrate the creation of web application using React+Vite and AWS Amplify, emphasizing easy setup for authentication, API, and database capabilities.

## Overview

This template equips you with a foundational React application integrated with AWS Amplify, streamlined for scalability and performance. It is ideal for developers looking to jumpstart their project with pre-configured AWS services like Cognito, AppSync, and DynamoDB.

## Features

- **Authentication**: Setup with Amazon Cognito for secure user authentication.
- **API**: Integrated with AWS AppSync for GraphQL APIs.
- **Database**: Configured with Amazon DynamoDB for scalable data storage.
- **Frontend**: Built with React and Vite for a fast and modern user interface.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/wan00000/to-do-list-app.git
   cd to-do-list-app
   ```

2. **Install dependencies**:

   Ensure you have [Node.js](https://nodejs.org/) installed, then run:

   ```bash
   npm install
   ```

3. **Configure Amplify**:

   Initialize the Amplify project:

   ```bash
   amplify init
   ```

   Follow the prompts to set up your environment.

4. **Deploy Amplify resources**:

   Push the configured resources to your AWS account:

   ```bash
   amplify push
   ```

5. **Start the development server**:

   ```bash
   npm run dev
   ```

   Open your browser and navigate to `http://localhost:3000` to see the application in action.

## License

This project is licensed under the MIT-0 License. See the [LICENSE](LICENSE) file for more details.

---

