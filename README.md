# Cloud-Based CRM System with AWS Lambda and DynamoDB

This is a Cloud-Based Customer Relationship Management (CRM) System built using AWS serverless services. The project demonstrates how to manage customer data efficiently with a web interface, leveraging AWS Lambda for backend logic, DynamoDB for data storage, and API Gateway for API management. Features include adding, editing, deleting, viewing, and exporting customer data to CSV, along with a dark mode toggle.

## Project Overview
- **Frontend**: Built with HTML, CSS, and JavaScript (`index.html`).
- **Backend**: Implemented with Python in `lambda_function.py` using AWS Lambda.
- **Database**: Stores customer data in a DynamoDB table (`CustomerTable`).
- **Deployment**: Hosted via AWS API Gateway.

## How to Use
1. Deploy the Lambda function with the provided code.
2. Set up the API Gateway with the specified resources (/add-customer, /get-customer, etc.).
3. Populate the DynamoDB table with sample data using the /populate endpoint.
4. Access the CRM interface by opening the API URL in a browser.

## Demo Video
Check out the video tutorial for this project:
https://youtu.be/MKF6kOBKVco
[![Watch the Video](https://img.youtube.com/vi/MKF6kOBKVco/0.jpg)](https://www.youtube.com/watch?v=MKF6kOBKVco)

## Future Enhancements
- Add user authentication with AWS Cognito.
- Implement advanced search using DynamoDB indexes.
- Integrate AWS S3 for file storage.

## Getting Started
- Download the code from this repository.
- Follow the AWS setup instructions in the video to deploy the project.

## Contact
For questions, feel free to open an issue or reach out via khanishkc@gmail.com.
