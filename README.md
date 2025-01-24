# Eventual

**Eventual** is a full-stack project for storing and visualizing events. It combines a FastAPI backend with a Node.js + React + Vite frontend.

## Key Features
- **Backend:** Built with FastAPI, providing a robust API for managing events.
- **Frontend:** Developed using Node.js, React, and Vite for a modern, responsive user interface.
- **Database:** MongoDB for efficient and scalable data storage.
- **Maps:** OpenStreetMap integration for interactive event location mapping.
- **Images:** Cloudinary for hosting and managing event images.
- **Authentication:** Firebase (OAuth) for secure Google authentication.

## Repository Structure
- `server/`: Contains the FastAPI backend.
- `client/`: Contains the Node.js + React + Vite frontend.

## Running Locally
To run the application locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/macorisd/eventual.git
   cd eventual
   ```

2. **Install Frontend Modules**
   - Run the batch file `install_node_modules.bat` to install all necessary Node.js modules for the frontend.

3. **Install Backend Dependencies**
   - Navigate to the `server` directory:
     ```bash
     cd server
     ```
   - Install the required Python packages using `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

4. **Start the Application**
   - Run the batch file `start_app.bat`.
   - This will open two terminal windows: one for the FastAPI backend and another for the React frontend.

## Deployment
The application is deployed on Vercel and can be accessed at: [Eventual on Vercel](https://ingweb-ev-p3-client.vercel.app/).

## Requirements
- Python (latest version recommended)
- Node.js (latest stable version)