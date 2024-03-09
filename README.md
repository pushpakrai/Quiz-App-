# Full Stack Developer Intern at Curlcrafters

## MERN Stack Quiz Application

Welcome to my internship task submission for the Full Stack Developer Intern position at Curlcrafters! Below, you'll find the details of the MERN Stack Quiz Application I've developed as part of my task.

## About

This project is a part of my internship task at Curlcrafters. It's a MERN (MongoDB, Express.js, React.js, Node.js) stack application aimed at creating, sharing, and playing quizzes. The goal of this project is to further my understanding of the React ecosystem and demonstrate my skills as a Full Stack Developer.

## Features

- **Create Quizzes**: Users can create quizzes and save them as drafts.
- **Publish Quizzes**: Draft quizzes can be published to the website for others to play.
- **Quiz Details**: Users can assign titles, descriptions, and categories to quizzes.
- **Multiple Choice Questions**: Quizzes support multiple choice questions.
- **Draggable Lists**: Ability to reorder questions or choices using draggable lists.
- **Favorite Quizzes**: Users can star/favorite quizzes for quick access.
- **Search Functionality**: Search for quizzes based on title or category.
- **Category Filters**: View quizzes by category.
- **User Authentication**: Login/Sign Up feature to access the quiz creator.
- **Mark Answers**: Users can mark answers among choices.
- **Update Quizzes**: Ability to update previously created quizzes.
- **Follow/Unfollow Users**: Logged in users can follow/unfollow other users.

## TODO

- **View Quiz Stats**: Display graphical representations of survey results (e.g., bar chart).
- **Multi-answer Questions**: Support questions with multiple correct answers.
- **UI Animations**: Implement animations to enhance user experience.
- **Optimistic UI Updates**: Implement optimistic UI updates for smoother interactions.
- **Timed Quizzes**: Introduce timed quizzes for added challenge.
- **Prompt Before Navigation**: Alert users before navigating away from quiz creator to prevent data loss.
- **Quiz Tags**: Allow users to assign tags to quizzes for better organization.
- **Upload Quiz Images**: Implement feature to upload quiz image thumbnails.
- **Rich Text Editor**: Integrate rich text editor for enhanced quiz creation.
- **Email Notifications**: Send email notifications to users for various events.
- **Edit Profile**: Allow users to edit their profile information.
- **Badge System**: Implement a badge system to award users for accomplishments.
- **Toast Notifications & Indicators**: Display toast notifications and indicators for user feedback.

## Tech Stack

- **Frontend**: React.js
- **State Management**: Redux Toolkit (or any other library for state management)
- **Backend**: Express.js
- **Authentication/Authorization**: Firebase
- **Database**: MongoDB

## Folder Structure

- `client/`: Contains frontend React code.
- `server/`: Contains backend Express.js code.
- `client/src/`: Contains React components and other frontend logic.
- `server/routes/`: Contains API routes for authentication and quiz handling.
- `server/models/`: Contains database models for MongoDB.

## How to Run

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/pushpakrai/Quiz-App-
   ```

2. Navigate to the project directory:
   ```
   cd Quiz-App-
   ```

3. Install dependencies:
   ```
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Configure environment variables:
   - Set up Firebase configuration in `server/.env` file.
   - Configure MongoDB connection in `server/.env` file.

5. Start the server:
   ```
   cd ../server
   npm start
   ```

6. Start the client:
   ```
   cd ../client
   npm start
   ```

7. Open your browser and go to `http://localhost:3000` to view the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

I would like to express my gratitude to Curlcrafters for providing me with this internship opportunity and allowing me to work on this exciting project. I also want to thank the open-source community for their valuable contributions to the technologies used in this project.
