
https://fontawesome.com/docs/web/use-with/react/

Add SVG core
    npm i --save @fortawesome/fontawesome-svg-core

Add icon packages
    npm i --save @fortawesome/free-solid-svg-icons
    npm i --save @fortawesome/free-regular-svg-icons
    npm i --save @fortawesome/free-brands-svg-icons


Add the react component
    npm i --save @fortawesome/react-fontawesome@latest


-----------------------------------------------------------------------------------------------------------------------


OBJECTIVE

Build a To-Do List application using React that allows users to add new tasks, mark tasks as completed, and delete tasks. This application will help you practice working with elements, components, props, JSX, and state in React.


REQUIREMENTS

Setup
    Start by creating a new React application using Create React App. Ensure your project structure is organized, with separate components for different parts of your application.

Task Component
    Create a Task component that represents a single task in the to-do list.
    Each task should display a description and have a checkbox to mark it as completed.
    Include a delete button (X) next to each task to allow users to remove tasks from the list.
    Use props to pass the task description, completion status, and event handlers (for marking as completed and deletion) from the parent component.

Task Input Form
    Implement a form at the top of your application that includes an input field for the task description and a submit button.
    Use the useState hook to manage the input state.
    On form submission, add the new task to the list of tasks. Ensure that the input field is cleared after submission.

Managing Tasks
    Use the useState hook in a parent component (e.g., App or TodoListManager) to manage the list of tasks. Initialize the state with an empty array.
    Tasks should be added to the state and rendered dynamically as they are submitted.
    Implement functionality to toggle the completion status of tasks and to delete tasks from the list. These actions should update the component's state accordingly.

Styling
    Apply basic styling to your application to improve usability and aesthetics. 
    Visually distinguish between completed and incomplete tasks (e.g., strike-through text for completed tasks).

Bonus Challenges (Optional)
    Implement task editing functionality.
    Add a filter option to display all tasks, only completed tasks, or only incomplete tasks. )))
    Persist the tasks in localStorage to keep the list between page reloads. )))

Evaluation Criteria
    Functionality: The application meets all the outlined requirements, including adding, completing, and deleting tasks. (20 Points)
    Code Quality: The code is well-structured, using appropriate React concepts and best practices. ( 5 points)
    User Interface: The application is user-friendly, with a clear distinction between different task states and responsive design. (5 Points)

Submission
    Submit your GitHub repository link in the blackboard submission area. Ensure your repository is public so it can be reviewed.

___________________________________________________________________________________________________________________________________


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
