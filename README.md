# Coding Exam Interface

This project is a coding exam interface designed for use in lab classrooms of faculties such as software and computer engineering. It is intended for students studying in these departments at universities. The interface resembles coding task sites like HackerRank, providing an environment for students to code live during exams.

## Features

- **Assignment and Code Editor**: The interface displays an assignment file and a code editor for the relevant programming language side by side.
- **Teacher's Control Panel**: Teachers can upload files containing instructions, student lists, and pre-written base code. They can also set the exam duration, exam name, and output directory for the final versions of the students' codes.
- **Student Login**: Students enter their student number, name, and an exam password to access the exam interface.
- **Code Execution**: The relevant programming language compiler is pulled from a Docker image based on the code file extension (.py, .java, .c) and runs in the code editor during the exam.
- **Real-time Monitoring**: Teachers can select a student from the student list to view their last run code and output during the exam.
- **Code Submission**: Students can run their code and submit the final version, which is then saved to the specified output directory with their student number as the filename.

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/coding-exam-interface.git
   cd coding-exam-interface
   ```

2. **Set up Docker**:
   Ensure Docker is installed on your system. If not, follow the instructions on [Docker's official website](https://www.docker.com/get-started).

3. **Build Docker images**:
   ```sh
   docker build -t coding-exam-interface .
   ```

4. **Run the Docker container**:
   ```sh
   docker run -p 8080:8080 coding-exam-interface
   ```

## Usage

### Teacher's Side

1. **Upload Files**:
   - Assignment file
   - Student list
   - Pre-written base code file

2. **Set Exam Details**:
   - Exam duration
   - Exam name
   - Output directory

3. **Start Exam**:
   - Click the "Start Exam" button to begin the exam.

4. **Monitor Students**:
   - Select a student from the list to view their last run code and output.

### Student's Side

1. **Login**:
   - Enter student number, name, and exam password.

2. **Code**:
   - Write and run code in the code editor.

3. **Submit**:
   - Click the "Submit" button to submit the final version of the code.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by coding platforms like HackerRank.
- Docker for containerization support.

## Contact

For any inquiries, please contact [yourname@domain.com](mailto:yourname@domain.com).
