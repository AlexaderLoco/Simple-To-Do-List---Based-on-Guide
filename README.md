# Simple Todo List Project

This is a simple single-page todo list application built with HTML, CSS, EJS, Express, and MongoDB. The application allows users to create, view, and delete tasks.

## Technologies Used

- **HTML**: Used for structuring the webpage.
- **CSS**: Used for styling the webpage.
- **EJS**: Embedded JavaScript templating for generating dynamic HTML content.
- **Express**: Web application framework for Node.js.
- **MongoDB**: A NoSQL database for storing todo list items.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/AlexaderLoco/Simple-To-Do-List---Based-on-Guide
```

2. Install dependencies:

```bash
npm install
```

3. Start the server: (also make sure that mongoDB is running)

```bash
node app.js
```

4. Open your web browser and navigate to `http://localhost:3000` to view the application.

## Features

- **Add Task**: Click the "+" button to add a new task to your todo list.
- **Delete Task**: Click the checkbox next to a task to delete it from the list.
- **Custom Lists**: Create custom lists by navigating to `http://localhost:3000/<list-name>`. Replace `<list-name>` with your desired list name.
- **Data Retention**: Your data will be saved in your machine for as long as mongoDB is not deleted.

## Acknowledgments

Special thanks to [The App Brewery](https://www.appbrewery.co/) for providing the project idea and guidance.
