# SnippetBox

A simple web application to manage and share code snippets. This project is based on the [Let's Go](https://lets-go.alexedwards.net/) textbook by Alex Edwards and serves as a learning tool for Go programming and web development concepts.

## Features

- Create, view, and delete code snippets
- User-friendly interface
- Secure and efficient handling of user data
- Built-in authentication system

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

- [Go](https://go.dev/) (version 1.19 or later)
- A database (e.g., MySQL or SQLite)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammed-el-amine-kichah/Snippet-Box.git
   ```

2. Navigate to the project directory:
   ```bash
   cd snippetbox
   ```

3. Install dependencies:
   ```bash
   go mod tidy
   ```

4. Set up the database:
   - Create a new database (e.g., snippetbox)
   - Update the connection string in `./config.json`

5. Run the application:
   ```bash
   go run ./cmd/web
   ```

6. Open your browser and visit:
   ```
   http://localhost:4000
   ```

## Technologies Used

- **Go**: Backend and application logic
- **HTML/CSS**: Frontend templates
- **MySQL**: Database management
- **TailwindCSS**: Styling 

## License

This project is for educational purposes only and follows the guidelines of the Let's Go textbook. All rights to the original content belong to Alex Edwards.

## Acknowledgments

- Special thanks to Alex Edwards for creating an excellent resource for learning Go
- Inspired by the SnippetBox project in the "Let's Go" textbook
