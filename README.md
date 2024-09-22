# Used Car Price Prediction

## Introduction:
This is a dynamic web application designed to let users efficiently predict car prices using machine learning models. The project scrapes relevant data from various car websites, processes it, and provides users with accurate price predictions. Below, you'll find the instructions to set up and run this project on your local machine.

## Prerequisites:
Ensure you have the following installed before proceeding:
- Node.js and npm: Download and install from [Node.js website](https://nodejs.org/).
- Python 3.7+: Install Python from [Python website](https://www.python.org/downloads/).
- MongoDB: Set up MongoDB locally or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
- FastAPI: Install FastAPI using `pip install fastapi`.

## Getting Started:
1. Clone the repository:
    ```bash
    git clone [https://github.com/your-repo/used-car-price-prediction.git](https://github.com/prabhnosingh/used-car-price-prediction.git)
    cd used-car-price-prediction
    ```

2. Frontend Setup:
    ```bash
    cd frontend
    npm install
    ```

3. Backend Setup:
    ```bash
    cd ../backend
    pip install -r requirements.txt
    ```

4. Run the Backend (Python + FastAPI):
    ```bash
    uvicorn main:app --reload
    ```

5. Run the Frontend (React.js):
    ```bash
    cd ../frontend
    npm start
    ```

6. Access the app:
    Open your browser and visit `http://localhost:3000`.
