# GitLens

## Introduction

GitLens is a powerful tool that enhances the Git experience directly within your code editor. It provides insights into your code's history, authorship, and much more, making it easier to understand the evolution of your project. This project is part of the Holberton School Portfolio Project.

## Project Purpose and Inspiration

The inspiration for GitLens came from the need to provide developers with deeper insights into their codebase. We wanted to create a tool that not only improves productivity but also makes it easier to understand and manage code history. Our goal was to address the common challenges developers face with version control and to enhance the overall Git experience.

## Team Members and Roles

- **Rachael Ojo** - Project Lead and Full Stack Developer
  - [LinkedIn](https://www.linkedin.com/in/rachael-ojo/)

## Technical Details
For the frontend of the application, HTML and CSS were selected for their simplicity and wide browser compatibility. HTML provides the structure of the web pages, while CSS handles the visual styling. These technologies allow for the creation of clean, responsive, and user-friendly interfaces without the need for additional frameworks.

For the backend, Flask was chosen due to its lightweight and modular design, which makes it an excellent choice for developing scalable web applications. Flask allows for the rapid development of server-side logic with minimal overhead, facilitating quick iterations and easy debugging. Its flexibility and simplicity make it suitable for both small-scale projects and complex applications.

SQLite3 was chosen as the database for its simplicity and efficiency in handling structured data. As a self-contained, serverless, and zero-configuration database, SQLite3 is perfect for development environments and smaller applications where setup and management overhead need to be minimized. Its integration with Flask is straightforward, enabling quick development and deployment cycles.

### Technology Stack

- **Frontend:** HTML, CSS
- **Backend:** Flask
- **Database:** sQLite3
- **Version Control:** Git, GitHub

### Architecture

The project follows a microservices architecture, where each service is responsible for a specific functionality. This approach ensures scalability and maintainability.

### Core Algorithms

One of the core algorithms we implemented is the enhanced blame annotation. This algorithm provides detailed information about each line of code, including the author, commit history, and timestamps.

### Why We Chose These Solutions

I chose React for its component-based architecture, which allows for reusable UI components. Flask was selected for the backend due to its lightweight nature and simplicity, making it easy to develop and maintain the server-side logic. SQLite3 was chosen for its ease of setup and ability to handle structured data efficiently, making it an excellent choice for development environments and small-scale applications.

## Challenges and Solutions

### Challenge 1: Real-time Collaboration

**Solution:** I implemented WebSockets to enable real-time which allows for instant updates and synchronization of code changes.

### Challenge 2: Detailed Blame Annotations

**Solution:** I developed a custom algorithm that integrates with Git to fetch detailed blame information. This involved parsing commit histories and associating each line of code with its respective author.

### Specific Example

One of the major challenges was handling large repositories with extensive commit histories. I optimized our algorithm by implementing lazy loading, which loads commit information on demand rather than all at once.

## Learnings and Future Iterations

This project has been a tremendous learning experience. I gained deeper insights into Git's inner workings and improved my skills in real-time data processing. For future iterations, I plan to:

- Integrate with more version control systems
- Enhance the UI/UX for better user experience
- Implement AI-driven code analysis for more insights

## Installation

To install and run the GitLens project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/rachaelojo/GitLens-landing-page.github.io.git
    ```
2. Navigate to the project directory:
    ```bash
    cd GitLens-landing-page.github.io
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm start
    ```

## Usage

1. Open your web browser and navigate to `http://localhost:8000`.
2. Explore the features of GitLens directly within your code editor.

## Screenshots

![GitLens Screenshot](path/to/screenshot.jpg)

## Contributing

I welcome contributions to the GitLens project! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add your commit message here"
    ```
4. Push your changes to your forked repository:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request to the main repository.

## Related Projects

- [Awesome READMEs](https://github.com/matiassingers/awesome-readme)

## Licensing

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Resources

- [What your code repository says about you](https://example.com/resource1)
- [Here’s an awesome list of READMEs](https://example.com/resource2)
