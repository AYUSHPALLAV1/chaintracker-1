# ChainTracker

ChainTracker is a cryptocurrency transaction analysis tool with a FastAPI backend and a React (Vite) frontend.

## Project Structure

- `backend/`: FastAPI application for transaction risk analysis, dataset loading, and model serving.
- `frontend/`: React frontend built with Vite and Tailwind CSS.

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 16+
- npm or yarn

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the backend server:
   ```bash
   uvicorn main:app --reload
   ```

### Frontend Setup

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

## Note on Datasets

The large dataset files (`.csv`, `.pkl`, `.npy`) are excluded from this repository due to their size. Ensure you have the necessary data files in `backend/data/` and models in `backend/models/` for the application to function correctly.
