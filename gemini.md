# Local Network Coding Exam Interface for University Labs

This project is a local network coding exam interface designed for university students in departments such as software and computer engineering. It provides a platform similar to coding challenge websites like HackerRank, allowing students to take coding exams in the university's lab classrooms.

## Features

-   **Teacher Interface:**
    -   Upload assignment files, student lists, and pre-written code templates.
    -   Set exam duration, name, and output directory for student submissions.
    -   Start and manage exams.
    -   Monitor student code and output in real-time.
-   **Student Interface:**
    -   Log in with student number, name, and exam password.
    -   View assignment instructions and code in a split-screen editor.
    -   Run code with language-specific compilers in Docker containers.
    -   Submit code for grading.
-   **Docker Integration:**
    -   Uses Docker containers to provide language-specific compilers for various programming languages (e.g., Python, Java, C).
    -   Ensures a consistent and isolated environment for code execution.
-   **Real-time Monitoring:**
    -   Teachers can monitor student progress and code execution in real-time.
    -   Students can see the output of their code as they run it.
-   **Automated Submission:**
    -   Student submissions are automatically saved to the specified output directory with their student numbers as filenames.

## How it Works

1.  **Teacher Setup:**
    -   The teacher uploads the assignment file, student list, and pre-written code template.
    -   The teacher sets the exam duration, name, and output directory.
    -   The teacher starts the exam.
2.  **Student Login:**
    -   Students log in with their student number, name, and exam password.
3.  **Coding:**
    -   Students view the assignment instructions and code in the split-screen editor.
    -   Students write and run code using the language-specific compiler in a Docker container.
4.  **Submission:**
    -   Students submit their code when they are finished.
    -   The submitted code is saved to the output directory.
5.  **Monitoring:**
    -   Teachers can monitor student progress and code execution in real-time.

## Technologies Used

-   [Programming Language] Python 
-   [Framework(s)] Django
-   Docker
-   HTML/CSS/JavaScript

## Getting Started

### Prerequisites

-   Docker
-   [Programming Language(s)] (e.g., Python, Java, C)
-   [Framework(s)] (e.g., Flask, Django, Spring Boot)

### Installation

1.  Clone the repository:

    ```bash
    git clone [repository URL]
    ```

2.  Install dependencies:

    ```bash
    [installation instructions]
    ```

3.  Run the application:

    ```bash
    [run instructions]
    ```

## Usage

1.  **Teacher:**
    -   Start the application and log in as a teacher.
    -   Upload the necessary files and set exam parameters.
    -   Start the exam.
2.  **Student:**
    -   Open the application in a web browser and log in with your credentials.
    -   Read the assignment instructions and start coding.
    -   Run and submit your code.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## **License**
This project is licensed under MIT License and **Anti-Capitalist Software License (ACSL)**.  
It is **strictly prohibited** to use this software for commercial purposes, profit-making ventures, or in support of capitalist organizations.  

However, contributions and modifications are **welcome** under the terms of this license.  

For full terms and conditions, see the [LICENSE](LICENSE) file or visit the official license page:  
🔗 [Anti-Capitalist Software License](https://anticapitalist.software)

## Contact

[Your Name] - [Your Email]
