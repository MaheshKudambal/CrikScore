# CrikScore

This project utilizes Spring Boot to fetch cricket match data from a website through web scraping techniques. The fetched data is then stored in a database for further processing. Additionally, the project provides an API endpoint to retrieve the stored match data upon receiving a request.

## Features:

1. *Web Scraping:* Utilizes web scraping techniques with Spring Boot to extract cricket match data from a specified website.
2. *Data Storage:* Stores the fetched cricket match data in a database for easy access and retrieval using Spring Data JPA.
3. *API Endpoint:* Provides a RESTful API endpoint to retrieve the stored match data in a structured format upon receiving an HTTP request.


## Technologies Used:

- Spring Boot: Java-based framework for building web applications.
- Spring Data JPA: Part of the Spring Data project, used for interacting with the database.
- Spring MVC: Model-View-Controller architecture for building web applications in Spring Boot.
- Jsoup: Java library for web scraping.
- Hibernate: Object-relational mapping framework used with Spring Data JPA for database interaction.
- RESTful API: Implementing RESTful principles for building the API endpoint.
- JSON: Data interchange format used for structuring the API responses.

## Getting Started:

To get started with using this project, follow the instructions below:

1. Clone the repository to your local machine.
2. Set up your database configuration in application.properties.
3. Run the Spring Boot application to fetch cricket match data and store it in the database.
4. Start the application server to run the API endpoint.
5. Make HTTP requests to the API endpoint to retrieve the stored match data.
