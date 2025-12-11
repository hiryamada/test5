# test5

FastAPI "Hello World" application with pytest tests.

## Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

The application will be available at `http://localhost:8000/`

Access the root endpoint to see "Hello World":
- URL: `http://localhost:8000/`
- Response: `{"message": "Hello World"}`

## API Documentation

FastAPI provides automatic interactive API documentation:
- Swagger UI: `http://localhost:8000/docs`
- ReDoc: `http://localhost:8000/redoc`

## Running Tests

Run the test suite with pytest:

```bash
pytest
```

For verbose output:

```bash
pytest -v
```