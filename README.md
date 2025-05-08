# FastAPI with Tailwind CSS and Bootstrap

This is a project that combines **FastAPI**, **Tailwind CSS**, and **Bootstrap** to create a web application with modern styling and a fast backend. Follow the instructions below to set up and run the project.

## Prerequisites

To run this project, you need to have the following software installed:

- **Python** (3.x or later)  
- **pip** (Python's package installer)
- **Node.js** (for building Tailwind CSS and managing frontend assets)
- **npm** (Node.js package manager)

You can check if you have the required software installed by running the following commands:

```bash
python --version
pip --version
node --version
npm --version
``` 

If any of these commands fail, you'll need to install the corresponding software before proceeding.

# Installation

## 1. Set up the Python environment

Clone the repository (if you haven’t already):

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### Create and activate a virtual environment (recommended to isolate Python dependencies):

On Windows:

```bash
python -m venv venv
.\venv\Scripts\activate
```

On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Python dependencies:
```bash
pip install -r requirements.txt
```

This will install the necessary backend dependencies (FastAPI, Uvicorn, etc.).

## 2. Set up the Frontend (Tailwind CSS & Bootstrap)

### Install Node.js dependencies:
In the project folder, run:
```bash
npm install
```

This will install Tailwind CSS, Bootstrap, and any other necessary frontend dependencies.

## 3. Run the Application

Once the dependencies are installed, you can run the application.

### Start the FastAPI backend:

```bash
uvicorn app:app --reload
```

The backend should now be running on http://127.0.0.1:8000.

### Build the Tailwind CSS:
If you are using Tailwind CSS in your project, you need to compile the CSS. Run:

```bash
npm run build
```

This will generate the necessary CSS files and make them available for the frontend.

## 4. Access the Application

Open your browser and go to http://127.0.0.1:8000 to view the application.