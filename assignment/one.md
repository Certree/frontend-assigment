**Problem Statement: Vue.js Coding Test**

**Task: Building an Advanced UserProfileCard Component**

**Description:**

You are tasked with building an advanced version of the `UserProfileCard` component using Vue.js. The component should include features such as dynamic data loading, Vuex integration for state management, and dynamic search functionality. The goal is to assess your proficiency in Vue.js concepts and your ability to handle complex scenarios in a Vue.js application.

**Requirements:**

1. **Asynchronous Data Loading:**
   - Integrate Vuex into the application and create a Vuex store with a module named `users`.
   - In the `users` module, manage the state for user details (name, email, profile picture) and user posts.
   - Use the provided [JSONPlaceholder](https://jsonplaceholder.typicode.com/) API to fetch user details and posts asynchronously.
   - Fetch and store user details (name, email, profile picture) and posts for the given `userId`.

2. **Dynamic Search Functionality:**
   - Implement a new component called `UserSearch` that includes an input field for searching users.
   - In the `UserProfileCard` component, implement a method to filter and display users based on the search term entered in the `UserSearch` component.
   - The search should trigger the asynchronous loading of user details and posts based on the search term.

3. **Dynamic Component Creation and Styling:**
   - Create a new component called `UserPost` to represent an individual post.
   - Use slots in the `UserProfileCard` component to allow users to customize the rendering of posts by providing their own `UserPost` component or custom content.
   - Style the components to provide a visually appealing and responsive design. Consider adding loading indicators for asynchronous data loading.

4. **Event Handling:**
   - Add a button within the `UserProfileCard` component to allow users to toggle the visibility of user posts.
   - Emit an event (`toggle-posts`) when the button is clicked to notify the parent component about the toggle action.

**Resources:**

1. [JSONPlaceholder API](https://jsonplaceholder.typicode.com/):
   - Use this API to fetch user details and posts. Example endpoints:
     - User details: `https://jsonplaceholder.typicode.com/users/{userId}`
     - User posts: `https://jsonplaceholder.typicode.com/posts?userId={userId}`

**Submission Guidelines:**

- Create the new github repository.
- Develop the solution in a Vue.js project structure (can use vue-cli with webpack or vite any).
- Document your code appropriately.
- Ensure that the solution is functional and styled.
- Provide a README file with instructions on how to run your application.
- (Optional) We recommended to use vuetify with tailwind for style your components but feel free to use any style framework.

**Evaluation Criteria:**

- Correct implementation of Vuex for state management.
- Successful integration with the JSONPlaceholder API for asynchronous data loading.
- Implementation of dynamic search functionality.
- Proper use of slots for dynamic component creation.
- Event handling for toggling user posts visibility.
- Styling and responsiveness of the components.
- Code organization and documentation.

**Note:**
- Feel free to use any additional libraries or tools if needed.
- If there are any ambiguities or uncertainties, make reasonable assumptions and document them in your code or README.
