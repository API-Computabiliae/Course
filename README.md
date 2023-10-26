**Quick GitHub Course**

# Introduction to GitHub

## What is GitHub?

GitHub is a source code hosting and collaboration platform that makes it easy to share and manage software projects.

## Step 1: Creating an Account

1. Go to [GitHub](https://github.com/) and click "Sign Up" to create an account.
2. Follow the instructions to set up your profile.

## Step 2: Creating a Repository

1. In the GitHub dashboard, click "New" to create a new repository.
2. Give it a name and choose visibility (public or private).
3. Click "Create Repository."

## Step 3: Cloning a Repository

1. In the desired repository, click the "Code" button and copy the repository link.
2. Open your terminal and navigate to the directory where you want to clone the repository.
3. Type `git clone [repository_link]` and press Enter.

## Step 4: Adding, Committing, and Pushing Changes

1. Make your changes to the files on your computer.
2. Use `git status` to check the changes.
3. Add the files with `git add [file_name]`.
4. Commit with `git commit -m "Commit message"`.
5. Push changes to the remote repository with `git push origin [branch]`.

## Step 5: Creating and Switching Branches

1. Create a new branch with `git checkout -b [branch_name]`.
2. Make your changes in the new branch.
3. Switch back to the main branch with `git checkout main`.
4. Merge changes with `git merge [branch_name]`.

## Step 6: Resolving Conflicts

1. If there are conflicts, Git will flag them.
2. Open the conflicting files and resolve the differences.
3. Add and commit the changes.

## Step 7: Creating Pull Requests

1. On GitHub, go to the repository page.
2. Click "Pull Requests" and then "New Pull Request."
3. Select the branch with the changes and create the pull request.



**Quick React Course**

# Introduction to React

## What is React?

React is a JavaScript library for building user interfaces, particularly for single-page applications where UI updates are frequent.

## Step 1: Setting Up a React App

1. Open your terminal and run the following command to create a new React app:
   ```bash
   npx create-react-app my-app
   ```
2. Navigate into the newly created directory:
   ```bash
   cd my-app
   ```
3. Start the development server:
   ```bash
   npm start
   ```
   Your React app will be available at http://localhost:3000.

## Step 2: Understanding Components

1. React apps are built using components - reusable, independent pieces of UI.
2. Create components in the `src` folder and use them to build your app.

## Step 3: Managing State and Props

1. State holds data that can change over time. Props pass data from a parent component down to a child component.
2. Use `useState` and `useEffect` hooks to manage state and side effects.

## Step 4: Routing with React Router

1. Install React Router with:
   ```bash
   npm install react-router-dom
   ```
2. Set up routes to navigate between different views.

## Step 5: Making HTTP Requests

1. Use `fetch` or libraries like Axios to make API calls from your React app.
2. Handle responses and update state accordingly.

## Step 6: Handling Forms and User Input

1. Use controlled components to manage form inputs.
2. Handle form submissions and update state with user input.

## Step 7: Styling with CSS-in-JS or CSS Modules

1. Choose a styling approach like CSS-in-JS libraries (Styled Components) or CSS Modules for scoped styling.

## Conclusion

You now have the basics to start building web applications with React! Explore more advanced topics like state management with Redux, context API, and testing to further enhance your React development skills.

## Conclusion

You now have the basics to start using GitHub! Explore more features like Issues, Actions, and GitHub Pages to enhance your collaborative development process.
