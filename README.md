
# Spring Boot Todo App

This is a simple Todo application built with Spring Boot. It allows users to manage their todos by adding, updating, and deleting tasks.

## Prerequisites

- Java Development Kit (JDK) 8 or above
- Maven
- MySQL or H2 Database (default configuration uses H2)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/todo-app.git
   ```

2. Navigate to the project directory:
   ```
   cd todo-app
   ```

3. Build the project using Maven:
   ```
   mvn clean install
   ```

4. Run the application:
   ```
   mvn spring-boot:run
   ```

5. Open your web browser and visit `http://localhost:8080` to access the Todo App.

## Usage

- To view all todos, go to `/list-todos`.
- To add a new todo, go to `/add-todo`.
- To update an existing todo, go to `/update-todo/{id}`.
- To delete a todo, go to `/delete-todo/{id}`.

## Technologies Used

- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf
- MySQL (or H2)

## Contributing

Contributions are welcome! If you find any issues or want to enhance the application, feel free to open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


Make sure to replace `your-username` in the clone command with your actual GitHub username.
