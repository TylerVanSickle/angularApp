```markdown
# angularApp

## Prerequisites

Before running the app, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (including npm)
- [Angular CLI](https://angular.io/cli)
- [JSON Server](https://github.com/typicode/json-server)

## Steps to Run the App

### 1. Initialize npm and Install Dependencies
Run the following command to set up the project:

```bash
npm init
```

### 2. Start the JSON Server
In a new terminal window, run the following to start the mock backend server:

```bash
json-server --watch db.json
```

This will serve the `db.json` file as your backend API.

### 3. Serve the Angular App
Now, in the root directory of the app, run:

```bash
ng serve
```

Your Angular app will now be available at `http://localhost:4200`.