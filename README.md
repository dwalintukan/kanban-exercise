# Kanban Exercise

Create a Kanban Board within React.

Example Kanban Board:
![image](https://user-images.githubusercontent.com/4350404/133505867-55f4052c-72e9-4803-861a-071fa41e55a4.png)

## Requirements

1. The board should have 4 Stages (columns) of Tasks:

   - `Backlog`
   - `To Do`
   - `Ongoing`
   - `Done`

2. Each Stage of Tasks should have an `unordered list of Tasks`.

3. Each Task should have `two navigation buttons`. If you want to use icons, check the [FontAwesome Icons section](#fontawesome-icons):

   1. `Back` - This moves the Task to the previous Stage in the sequence, if possible. This button is disabled if the Task is in the first Stage.
   2. `Forward` - This moves the Task to the next Stage in the sequence, if possible. This button is disabled if the Task is in the last Stage.

4. Each Task has these properties:

   1. `id` - The unique identifier for a Task.
   2. `name` - The name of Task.
   3. `stage` - The Stage of the Task.
   4. `assignee` - The person the Task is assigned to.

5. Have a `Form` to be able to add a new Task. When inserting a new Task, it should appear in the `backlog`.

## FontAwesome Icons

Search icons here:
[https://fontawesome.com/icons?d=gallery](https://fontawesome.com/icons?d=gallery)

Example:

```js
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faCoffee } from '@fortawesome/free-solid-svg-icons'

function SomeComponent() {
  return (
    <div>
      <FontAwesomeIcon icon={faCoffee} />
    </div>
  );
}
```

# Create React App (React App Boilerplate)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
