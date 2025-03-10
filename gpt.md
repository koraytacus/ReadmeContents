# **Coding Exam Platform**

## **Overview**
The Coding Exam Platform is a specialized local network-based system designed for university-level software and computer engineering students. It provides a structured and secure coding examination environment, similar to online coding challenge platforms like HackerRank, ensuring fairness and efficiency in programming assessments.

## **Key Features**

### **Instructor Capabilities**
- **Exam Setup:**
  - Uploads essential files before the exam:
    - **Assignment File:** Contains problem statements and exam instructions.
    - **Student List File:** Specifies the students participating in the exam.
    - **Pre-prepared Code File:** Includes starter code in the designated programming language (.py, .java, .c, etc.).
  - Configures key exam parameters:
    - **Exam Duration**
    - **Exam Name**
    - **Output Directory:** Defines the location where students' final submissions are stored with their student numbers.
- **Live Monitoring:**
  - Tracks students' progress in real-time.
  - Views the most recent code submissions and execution results of individual students.

### **Student Capabilities**
- **Secure Login:**
  - Authenticates using:
    - **Student Number**
    - **Full Name**
    - **Exam Password** (predefined by the instructor)
- **Coding Environment:**
  - **Left Panel:** Displays the assignment instructions.
  - **Right Panel:** Provides an integrated code editor for real-time programming.
- **Execution Environment:**
  - Runs code within a **Docker container**, dynamically selecting the appropriate compiler/interpreter based on the assigned programming language.
- **Submission System:**
  - Allows students to execute and test their code.
  - Final submissions are securely stored in the instructor-specified directory.

## **Technical Architecture**
- **Backend:** Handles user authentication, exam configuration, and file management.
- **Frontend:** Provides an interactive and intuitive coding interface.
- **Docker Integration:** Ensures an isolated and standardized execution environment for different programming languages.
- **Local Network Deployment:** Operates entirely within the university’s lab infrastructure, ensuring a controlled and secure examination setting without internet dependency.

## **Workflow**
1. The instructor sets up the exam, defining the necessary configurations and uploading required files.
2. Students log in securely using their credentials.
3. The exam interface loads, allowing students to write, execute, and test their code.
4. The instructor monitors students' progress and reviews real-time code execution results.
5. Students submit their final solutions, which are automatically stored in the designated output directory.
6. The exam concludes either upon time expiration or manual termination by the instructor.

## **Potential Enhancements**
- **Automated Grading System:** Enables automatic evaluation based on predefined test cases.
- **Plagiarism Detection Mechanism:** Ensures academic integrity by identifying similar code submissions.
- **Expanded Language Support:** Adds compatibility for additional programming languages.

## **License**

This project is licensed under the **Anti-Capitalist Software License (ACSL)**.  
It is **strictly prohibited** to use this software for commercial purposes, profit-making ventures, or in support of capitalist organizations.  

However, contributions and modifications are **welcome** under the terms of this license.  

For full terms and conditions, see the [LICENSE](LICENSE) file or visit the official license page:  
🔗 [Anti-Capitalist Software License]([https://github.com/hxr404/ACSL](https://anticapitalist.software))

For further inquiries or contributions, please submit a pull request or reach out via the project's repository.
