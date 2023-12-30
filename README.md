# SparkVibe

SparkVibe is a dynamic study group app designed to facilitate seamless collaboration among students, allowing them to form study groups based on their enrolled courses. With real-time communication, a user-friendly interface, and smart group recommendations, SparkVibe aims to enhance the overall learning experience for students.

## Technologies Used

- **Frontend:**
  - React: A JavaScript library for building user interfaces.
  - Next.js: A React framework for server-side rendering and routing.
  - Bootstrap: A front-end framework for responsive and mobile-first web development.

- **Backend:**
  - Node.js: A JavaScript runtime for server-side development.
  - Express: A web application framework for Node.js.
  - MongoDB: A NoSQL database for efficient data storage and retrieval.

- **Real-time Communication:**
  - Pusher API: Enables real-time communication and updates within study groups.

## Project Goals

### 1. Seamless Collaboration

SparkVibe focuses on providing students with a platform where they can effortlessly collaborate with their peers. The app allows users to create and join study groups based on the courses they are currently enrolled in.

### 2. Real-time Communication

To ensure effective communication within study groups, SparkVibe integrates the Pusher API. Real-time updates and messaging enhance the collaborative learning experience by allowing group members to interact seamlessly.

### 3. User-Friendly Interface

The user interface is crafted using React, NextJS, and Bootstrap to offer an intuitive and aesthetically pleasing experience. The design prioritizes user accessibility, making it easy for students to navigate and utilize SparkVibe's features.

### 4. Data Management

MongoDB is employed for robust data management, ensuring scalability and reliability as the user base and data volume grow. The database efficiently stores and retrieves information related to user profiles, courses, and study groups.

### 5. Smart Group Recommendations

One of the unique features of SparkVibe is its smart notification system. When a user, such as John, enrolls in new courses for the upcoming term, the app intelligently identifies previous group mates who share those courses. John receives a personalized notification:

```markdown
# Smart Group Recommendation

Hey John,

We noticed that some of your previous group mates from the fall term have enrolled in the same courses as you for the winter term. Do you want to add them to a new group or form a group with them? Enhance your learning experience by collaborating with familiar faces!

[Add to Group] | [Create New Group]
