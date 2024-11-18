### CASHCARD_API
This is a Spring boot API that simulates a cash card. It allows you to create a cash card, get a cash card, edit a cash card, delete a cash card.
I have implemented tests before writing an actual REST APIs(TDD).

### Technologies
- Spring Boot web
- Spring Data JDBC
- Spring Security
- H2 Database
- Gradle

### How to run
- Clone the repository
- Run the command `./gradlew bootRun` to start the application
- Run the command `./gradlew test` to run the tests
- The application will start on port 8080
- The url to access the application is `http://localhost:8080`

### Endpoints
- POST `/cashcards` - Create a cash card
- GET `/cashcards` - Get all cash cards
- GET `/cashcards/{id}` - Get a cash card by id
- PUT `/cashcards/{id}` - Update a cash card by id
- DELETE `/cashcards/{id}` - Delete a cash card by id