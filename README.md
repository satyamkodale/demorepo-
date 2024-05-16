<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Java Backend Task Overview</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #333;
        }

        code {
            background-color: #f4f4f4;
            padding: 5px;
            border-radius: 5px;
            font-family: Courier, monospace;
        }

        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }

        .endpoint {
            margin-bottom: 20px;
        }

        .failure-scenarios {
            margin-top: 20px;
        }

        .error-message {
            color: #ff0000;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>Java Backend Task Overview</h1>

    <p>This project focuses on building a Java backend application using the Spring Boot framework. The objective is to develop a robust system for managing user data through a set of RESTful APIs. The application will handle user creation, retrieval, deletion, and updating operations, ensuring data integrity, security, and efficiency throughout the process.</p>

    <h2>Key Features</h2>
    <ul>
        <li>RESTful Endpoints: The application provides RESTful APIs for creating, retrieving, updating, and deleting user records.</li>
        <li>Logging: Logging functionality is implemented using the SLF4J logger framework to track application events and errors.</li>
        <li>Custom Exception Handling: Custom exception handling is implemented for each endpoint to provide meaningful error messages and improve error traceability.</li>
        <li>Validation: Input data validation is enforced using Spring Starter Validation to ensure the integrity and validity of user-provided data.</li>
        <li>Bulk Updation: Bulk updation functionality is implemented in accordance with project guidelines to efficiently update user records when necessary.</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li>Java: Version 17</li>
        <li>Spring Boot: Version 3.2.5</li>
    </ul>

    <h2>Installation Guide</h2>
    <h3>Prerequisites</h3>
    <ul>
        <li>Java JDK 17 or higher installed on your system</li>
        <li>Maven installed on your system</li>
    </ul>

    <h3>Steps</h3>
    <ol>
        <li>Clone the Repository:</li>
        <pre><code>git clone https://github.com/satyamkodale/DailypeTask.git</code></pre>
        <li>Navigate to the Project Directory:</li>
        <pre><code>cd DailypeTask</code></pre>
        <li>Build the project:</li>
        <pre><code>mvn clean install</code></pre>
        <li>Run Application:</li>
        <pre><code>mvn spring-boot:run</code></pre>
    </ol>

    <h2>API Endpoints Documentation</h2>

    <!-- Each endpoint documentation goes here -->
    <!-- You can wrap each endpoint in a div with class "endpoint" for styling purposes -->

</div>
</body>
</html>
