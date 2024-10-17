## Epic 1: Project Setup and Basic Structure

### Task 1.1: Create a New C# Console Application

-   **Description**: Set up the initial project structure in Visual Studio or any other preferred IDE. Create a console application called `MovieFestival`.
-   **Acceptance Criteria**:
    -   A new C# console project is created with the correct name.
    -   Ensure that the project runs and outputs a simple "Hi" message to the console.

### Task 1.2: Implement `Genre` Class

-   **Description**: Create the `Genre` class with the required properties and methods.
-   **Acceptance Criteria**:
    -   `Genre` class with `Name` property is implemented.
    -   `GetData()` method returns the first and last letter of the genre's name.

### Task 1.3: Implement `Movie` Class

-   **Description**: Create the `Movie` class with properties like `Title`, `Genre`, and `Length`. Implement the `GetData()` method for movie details.
-   **Acceptance Criteria**:
    -   `Movie` class with necessary properties is implemented.
    -   `GetData()` returns the movie title, length, and genre acronym.

---

## Epic 2: Program and Festival Logic

### Task 2.1: Implement `Program` Class

-   **Description**: Implement the `Program` class with properties for the date and a list of movies. Add logic for calculating total program duration and formatting output using `GetData()`.
-   **Acceptance Criteria**:
    -   `Program` class is created with properties for `Date` and `Movies`.
    -   `AddMovie()` method adds a movie to the program's movie list.
    -   `GetData()` method returns the program's total duration and formatted movie details.

### Task 2.2: Implement `Festival` Class

-   **Description**: Implement the `Festival` class with properties for the festival's name and a list of programs. Add logic for adding programs and generating the festival's output.
-   **Acceptance Criteria**:
    -   `Festival` class with properties for `Name` and `Programs` is implemented.
    -   `AddProgram()` method adds a program to the list of programs.
    -   `GetData()` method returns the formatted festival details, including the total number of movies and all programs' details.

---

## Epic 3: User Input and Application Flow

### Task 3.1: Implement Movie and Program Creation Functions

-   **Description**: Implement `CreateMovie()` and `CreateProgram()` methods to prompt the user for input and create `Movie` and `Program` instances.
-   **Acceptance Criteria**:
    -   `CreateMovie()` function prompts the user for title, length, and genre, and returns a `Movie` instance.
    -   `CreateProgram()` function prompts the user for a date and returns a `Program` instance.

### Task 3.2: Main Application Flow

-   **Description**: In the main function, prompt the user for the festival name, number of movies, and movie details. Output the festival details after all data is entered.
-   **Acceptance Criteria**:
    -   The user is prompted for the festival name and number of movies.
    -   The application collects data for each movie and adds them to a program.
    -   After all data is collected, the formatted festival details are output to the console.

---

## Epic 4: Testing

### Task 4.1: Setup Test Project

-   **Description**: Create a separate xUnit test project to house unit tests for the MovieFestival project.
-   **Acceptance Criteria**:
    -   xUnit test project is created and added to the solution.
    -   Reference to the `MovieFestival` project is added.

### Task 4.2: Write Unit Tests for `Genre` Class

-   **Description**: Write unit tests for the `Genre` class to ensure `GetData()` works as expected.
-   **Acceptance Criteria**:
    -   Test cases for different genre names, including empty strings and single characters, are covered.
    -   All test cases pass.

### Task 4.3: Write Unit Tests for `Movie` Class

-   **Description**: Write unit tests for the `Movie` class to ensure `GetData()` returns properly formatted movie data.
-   **Acceptance Criteria**:
    -   Test cases for various movie titles, lengths, and genres are covered.
    -   All test cases pass.

### Task 4.4: Write Unit Tests for `Program` Class

-   **Description**: Write unit tests for the `Program` class to verify the movie list addition and the `GetData()` output.
-   **Acceptance Criteria**:
    -   Test cases for calculating total program duration and movie formatting are covered.
    -   All test cases pass.

### Task 4.5: Write Unit Tests for `Festival` Class

-   **Description**: Write unit tests for the `Festival` class to ensure programs are added correctly and the festival's `GetData()` returns properly formatted details.
-   **Acceptance Criteria**:
    -   Test cases for adding programs and calculating total movies are covered.
    -   All test cases pass.

---

## Epic 5: Documentation and Cleanup

### Task 5.1: Add Comments and Documentation

-   **Description**: Add inline comments to all classes and methods to explain their functionality. Provide high-level documentation for the project.
-   **Acceptance Criteria**:
    -   All methods and classes are commented.
    -   A `README.md` file is created with an overview of the project, how to run it, and any other necessary information.

### Task 5.2: Code Refactoring and Cleanup

-   **Description**: Refactor the code to ensure clean, readable, and maintainable code, following best practices.
-   **Acceptance Criteria**:
    -   All code is formatted correctly, and unnecessary code is removed.
    -   Ensure all classes and methods follow the SOLID principles.
