# GameToDo: The Ultimate Gamified To-Do List

**Step into the enchanting world of GameToDo! Merge your daily tasks with an exciting adventure where you raise and care for your very own digital companion. Complete tasks to earn rewards, upgrade your town, and keep your character happy and healthy. But beware! Neglecting your to-dos will result in dire consequences. Are you ready to turn your chores into epic quests and become the hero of your own life?**

## Stack

### Backend
- **Database**: MongoDB using Mongoose
- **Server**: GraphQL server
- **Authentication**: Store user info with JWT
- **Data**: Manage to-dos and track character state

### Frontend
- **Framework**: Next.js
- **Styling**: Tailwind CSS
- **Features**:
  - **Tamagotchi-style Interface**: Care for your digital companion as you complete tasks.
  - **Checklist of To-Dos**: Keep track of your tasks and mark them off as you complete them.
  - **Interactive Buttons**: Quick actions for common to-dos and the ability to add custom tasks.
  - **Daily Interactions**: Feed your character or clean its environment by completing tasks; lose HP if tasks are neglected.
  - **Lose Condition**: If all HP is lost, your character resets and you start anew.

## Development Steps

### Backend
1. **Set Up MongoDB and Mongoose**:
   - Install MongoDB and set up a connection using Mongoose.
   - Define schemas and models for users, tasks, and character state.

2. **Create GraphQL Server**:
   - Set up a GraphQL server using a framework like Apollo Server.
   - Define type definitions and resolvers for querying and mutating tasks, user info, and character state.

3. **Implement Authentication**:
   - Use JWT for user authentication.
   - Create middleware for verifying tokens and protecting routes.

4. **Build API Endpoints**:
   - Create GraphQL queries and mutations for managing to-dos, character state, and rewards.

### Frontend
1. **Set Up Next.js and Tailwind CSS**:
   - Initialize a Next.js project.
   - Configure Tailwind CSS for styling.

2. **Design UI Components**:
   - Create components for displaying the Tamagotchi character, task list, and town upgrades.
   - Develop buttons for adding, completing, and managing to-dos.

3. **Implement State Management**:
   - Use a state management library (e.g., Redux or Context API) to manage user state, tasks, and character health.
   - Connect the frontend to the GraphQL backend to fetch and update data.

4. **Add Game Logic**:
   - Implement logic for task completion, reward allocation, and HP management.
   - Create conditions for losing HP and triggering negative events.

5. **Deploy the Application**:
   - Deploy the backend server to a platform like Heroku or Vercel.
   - Deploy the frontend to a static site hosting service like Vercel.

## Additional Features
- **Upgrades**: Add more features for town and equipment upgrades.
- **Classes and Heroes**: Develop different classes or heroes with unique abilities.
- **Bonus Quests**: Implement random bonus quests from NPCs for extra rewards.
