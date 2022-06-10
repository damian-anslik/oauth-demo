Sample client-server implementation of the OAuth 1.0 protocol.

# Running the authentication server

The authentication server is built using FastAPI and can be started locally using uvicorn.

1. Create and activate a new virtual environment
2. Install project dependencies using: `pip install -r requirements.txt`
3. Run the following command to start the local server using uvicorn: `uvicorn main:app --app-dir app`