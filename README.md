Data Visualization Dashboard
Project Description
The Data Visualization Dashboard is a web application that provides users with the ability to visualize and analyze data through various filters and chart types. It connects to a MongoDB database to fetch and display data related to various global topics, including environmental impacts, social issues, and economic trends. The application leverages React for the front end and Express.js for the back end, facilitating seamless data communication and dynamic rendering of visualizations.

Key Features
Dynamic Filtering: Users can filter data by region, country, end year, topics, sector, PEST analysis, source, and SWOT analysis.
Data Visualization: The dashboard provides multiple visualization options, including bar charts and pie charts, to help users understand trends and insights at a glance.
Pagination: Users can navigate through large datasets with pagination controls.
Responsive Design: The application is designed to be responsive, ensuring a good user experience across different devices.
Tech Stack
Frontend
React: A JavaScript library for building user interfaces, which allows for the creation of reusable UI components.
Axios: A promise-based HTTP client for the browser and Node.js, used for making requests to the backend API.
D3.js: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.
CSS: For styling the application and ensuring a pleasant user experience.
Backend
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine, allowing for the execution of JavaScript server-side.
Express.js: A web application framework for Node.js, used for building RESTful APIs and handling routing.
Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js, used to define data schemas and interact with the MongoDB database.
dotenv: A zero-dependency module that loads environment variables from a .env file into process.env.
Database
MongoDB: A NoSQL database that uses a flexible, JSON-like format to store data, allowing for dynamic data modeling.
Development Tools
Git: Version control system for tracking changes in the source code.
GitHub: A platform for version control and collaboration, enabling developers to work together on projects.
Render: A cloud hosting platform used for deploying the application.
How It Works
User Input: Users select filters and options from dropdowns and text inputs on the dashboard.
Data Fetching: Upon applying the filters, the application sends a request to the backend API, which queries the MongoDB database for relevant data.
Data Processing: The backend processes the filters and returns the filtered data set.
Visualization: The frontend uses D3.js to render the data into interactive visualizations based on the selected chart type.
User Interaction: Users can navigate between pages of data, apply different filters, and switch between chart types to gain insights from the data.
Dashboard Insights
The dashboard provides a comprehensive view of various global data trends, allowing users to:

Analyze the intensity of different topics based on countries and regions.
Understand how different sectors are affected by various factors.
Gain insights into the relevance and impact of different data points over time.
Visualize the data in a way that facilitates easy comparison and understanding.
Application Deployment Link- https://mern-data-visualisation-dashboard.onrender.com/
