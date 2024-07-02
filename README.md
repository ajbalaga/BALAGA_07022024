# .NET Core Coding Challenge


## Overview
Welcome to the repository for our .NET Core Coding Challenge submission. This project showcases a robust, RESTful web service for secure file processing with advanced tracking and reporting capabilities.

## Features
- Secure Web Service: Implemented using ASP.NET Core, ensuring robust security measures.
- File Processing: Supports CSV and JSON formats:
  
  - CSV Processing: Calculates aggregate metrics for Employee Count per Department. This involves computing the Average Employee Count per Department based on data from the second column of the CSV file.
  - JSON Processing: Executes dynamic data transformations on Personal Details based on specified criteria. It selectively retrieves data for individuals whose names contain "John" and who are 30 years old.
- API Key Authentication: Implements secure API Key validation middleware for endpoint protection.

- File Tracking and Reporting: Offers detailed tracking and reporting functionalities:
  - Tracks processed file count and essential metadata (filename, processing time).
  - Provides endpoints for retrieving processing details and summary reports.
- Containerization: Dockerizes the application for effortless deployment and scalability.

## Setup
Ensure you have the following prerequisites installed:

 - [.NET 8.0 ](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

 - [Docker](https://docs.docker.com/engine/install/)

 - [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/)


Clone the repository and navigate to the project directory.
```bash
https://github.com/ajbalaga/BALAGA_07022024.git
```

## Steps to run the API
1. Open the solution using Visual Studio
2. Run Docker Desktop
3. Right-click the Dockerfile inside the CodingChallengeAPI and click "Build Docker Image"
4. Click Run Container (Dockerfile) in Release mode
5. The browser will automatically open and then click the Authorize button to enter the API KEY 
 my sample API key is Kj3GhPqR7sT5W8zx9Ly7E4nF1aB2cD3 
6. the /CodingChallenge/processFile endpoint will accept multiple files either CSV files or JSON File and then click the Execute button to get the results

Note: The sample input format for JSON file and CSV file are SampleCSVFile.csv and SampleJsonFile.json 

