# React Todo App

This repository contains the implementation for loading todos in a simple Todo App built using React. The app is designed to interact with an API to perform CRUD operations on todos.

## Features Implemented

### Load Todos

- Implemented the functionality to load todos from the API.
- Utilized the fetchClient module to interact with the API.
- Displayed a spinner immediately when loading todos to notify the user of the ongoing action.
- Implemented error handling to display appropriate error messages in case of API errors.
- Implemented filtering functionality to filter todos by status (All / Active / Completed).
- Applied proper styling to highlight the selected filter link.

### Error Messages

- Displayed notifications with appropriate error messages at the bottom in case of any API errors.
- Provided a close button to manually dismiss the notification.
- Automatically hid the notification after 3 seconds.
- The notification is hidden before any subsequent API requests.

#### [DEMO LINK](https://mariasnegireva.github.io/to-do-app/)

#### Instructions to Run the Application

Clone the project

```bash
  git clone
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the development server with the following command

```bash
  npm start
```

Open your web browser and visit <http://localhost:3000> to view the application.
