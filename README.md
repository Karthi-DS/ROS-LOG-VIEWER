React Application
Setup Instructions
Clone the repository:


git clone [https://github.com/your-repository/react-app.git](https://github.com/Karthi-DS/ROS-LOG-VIEWER.git)
cd react-app
Install dependencies:


npm install
Start the development server:


npm start
Access the app:

The React application will be available at http://localhost:3000.
Tools Used
React.js: Frontend framework for building interactive UIs.
Node.js: JavaScript runtime for running the app.
Axios: HTTP client for making requests to the FastAPI backend.
Tailwind CSS: Utility-first CSS framework for styling.
Features
Data Management: Fetches log data from the FastAPI backend.
Filtering: Allows users to filter logs by node, message, and severity.
Pagination: Navigates through log data using page controls.
File Upload: Uploads log files and updates the UI in real-time.
Delete Files: Deletes all stored files and updates the UI.
Download Filtered Logs: Generates and downloads filtered logs as a CSV file.
README for FastAPI Backend
FastAPI Application
Setup Instructions
Clone the repository:

cd backend

Install dependencies:


pip install -r requirements.txt
Run the API:


uvicorn main:app --reload
Access the API:

The FastAPI backend will be available at http://localhost:8000.
Tools Used
FastAPI: Fast and modern web framework for building APIs in Python.
Uvicorn: ASGI server for running FastAPI.
Pydantic: Data validation using Python type annotations.
Features
File Upload: Receives and processes log files from the frontend.
File Deletion: Deletes all stored log files.
CSV Generation: Creates downloadable CSV files from filtered logs.
Data Filtering: Filters logs by date, severity, node, and message.
Pagination: Provides paginated responses for large data sets.
