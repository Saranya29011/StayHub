 ## **Requirements** 
### 1. **Node.js Installation**  
Ensure Node.js is installed on your system before starting the project.  
Download the latest version (e.g., 18.x or your preferred version) from the official Node.js website: [Node.js Download](https://nodejs.org/).

---

### 2. **Required Node.js Libraries**  
You will need the following libraries for your frontend and backend functionality. Install them using `npm` (Node Package Manager).

#### For the **Frontend** (React):
In the `frontend` directory of your project, run the following commands to install the required dependencies:

- **Axios**: For making HTTP requests to your Express backend.
  ```bash
  npm install axios@1.5.0
  ```

- **React Router DOM**: For managing page navigation between components.
  ```bash
  npm install react-router-dom@6.6.1
  ```

- **React Google Maps API**: For integrating Google Maps in your React app.
  ```bash
  npm install @react-google-maps/api@2.2.0
  ```

- **React Bootstrap** (optional, for styling UI components with Bootstrap):
  ```bash
  npm install react-bootstrap@2.7.0
  ```

---

#### For the **Backend** (Express):
In the `backend` directory of your project, run the following commands to install the necessary dependencies:

- **Express**: For setting up the backend server.
  ```bash
  npm install express@4.18.2
  ```

- **Mongoose**: For interacting with MongoDB from the backend.
  ```bash
  npm install mongoose@6.7.2
  ```

- **CORS**: To handle cross-origin requests between your frontend and backend.
  ```bash
  npm install cors@2.8.5
  ```

---

### 3. **Google Maps API Setup**  
You will need to create an account in Google Cloud Platform to get an **API key** for Google Maps.

1. Go to [Google Cloud Platform](https://cloud.google.com/).
2. Create a new project.
3. Enable the **Google Maps JavaScript API**.
4. Generate an API key from the **Credentials** section.
5. Integrate the API key into your React app using the `@react-google-maps/api` library.

---

### 4. **Specific Version Information**  
For reproducibility, ensure you're using these specific versions of the required libraries:

#### Frontend:
- **React**: `18.2.0` (or latest stable version)
- **Axios**: `1.5.0`
- **React Router DOM**: `6.6.1`
- **React Google Maps API**: `2.2.0`
- **React Bootstrap**: `2.7.0` (optional)

#### Backend:
- **Express**: `4.18.2`
- **Mongoose**: `6.7.2`
- **CORS**: `2.8.5`

---

### 5. **Backend Database**  
Ensure you have MongoDB installed on your machine, or use a cloud-based solution like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

- **MongoDB**: For the backend database to store user data and place details.

  To install MongoDB locally, refer to the official MongoDB installation guide: [MongoDB Installation](https://www.mongodb.com/docs/manual/installation/).

---

### 6. **Run the Project**  
Once the dependencies are installed, follow these steps to start your project:

1. **Start the Express backend**:
   - In your `backend` directory, run:
     ```bash
     node app.js
     ```
   - This will start the server on port `4002`.

2. **Start the React frontend**:
   - In your `frontend` directory, run:
     ```bash
     npm start
     ```
   - This will start the React development server on port `3000` (or another available port).

---


