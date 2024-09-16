# CRM Dashboard

A modern, full-featured CRM dashboard built to manage customer relationships efficiently, using a wide range of web technologies. This project demonstrates the integration of both backend and frontend systems to provide a powerful and scalable solution.

## Features
- **Dynamic Data Visualizations**: Utilize Nivo for visually appealing charts and graphs.
- **User-Friendly UI**: Built with Material UI and Material UI Data Grid for a responsive and accessible interface.
- **State Management**: Redux Toolkit and Redux Toolkit Query for efficient and scalable state management.
- **Date Selection**: Integrated React Date Picker for easy date handling in forms and reports.
- **Authentication**: Secure JWT-based authentication for user login and access control.
- **Database**: MongoDB for storing and managing customer data, with Mongoose as an ORM and MongoDB Aggregate for advanced queries.
- **Routing**: React Router for smooth page navigation.
- **Deployment**: Deployed using Render and Railway for cloud-based hosting and scalability.

## Technologies Used
- **Backend**: [Node.js](https://nodejs.org/en/download/), [Nodemon](https://github.com/remy/nodemon)
- **Frontend**: [React](https://reactjs.org/), [Material UI](https://mui.com/material-ui/getting-started/overview/), [Nivo](https://nivo.rocks/)
- **State Management**: [Redux Toolkit](https://redux-toolkit.js.org/), [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview)
- **Database**: [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/), [MongoDB Aggregate](https://www.mongodb.com/docs/manual/reference/aggregation/)
- **Utilities**: [React Router](https://reactrouter.com/), [React Date Picker](https://reactdatepicker.com/), [Dotenv](https://github.com/motdotla/dotenv)
- **Authentication**: [JsonWebToken](https://github.com/auth0/node-jsonwebtoken)
- **Deployment**: [Render](https://render.com/), [Railway](https://railway.app/)
- **Development Tools**: [VSCode](https://code.visualstudio.com/), [NPX](https://www.npmjs.com/package/npx)

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/HarshVardhan12102002/LogixCRM-MERN-Stack.git
    cd LogixCRM-MERN-Stack
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the following:
    ```plaintext
    MONGO_URI=your-mongodb-connection-string
    JWT_SECRET=your-secret-key
    ```

4. Run the development server:
    ```bash
    npm start
    ```

5. For hot-reloading, use Nodemon:
    ```bash
    npm run dev
    ```

## Usage
- Access the dashboard by navigating to `http://localhost:3000` in your browser.
- Sign in using your credentials to start managing customer data, visualizing reports, and tracking metrics.

  
<h3><b>Live Demo:</b> https://logixcrmadmin-harsh.onrender.com</h3>

