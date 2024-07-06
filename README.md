# Daraja API Test Project

This project demonstrates the usage of Safaricom's Daraja API for various mobile money operations using Flask in Python.

## Setup

1. **Environment Variables**:
   - Create a `.env` file in the project root.
   - Add the following variables obtained from Safaricom developer website:
     ```
     CONSUMER_KEY=<your_consumer_key>
     CONSUMER_SECRET=<your_consumer_secret>
     BASE_URL=<your_ngrok_url>
     PHONE_NUMBER=<your_phone_number>
     ```

2. **Dependencies**:
   - Ensure Python 3.x is installed.
   - Install dependencies listed in `requirements.txt` using:
     ```
     pip install -r requirements.txt
     ```

3. **Run the Application**:
   - Start the Flask application:
     ```
     flask run --host=0.0.0.0 --port=5000
     ```

## Notes

- Replace placeholders in environment variables (`CONSUMER_KEY`, `CONSUMER_SECRET`, `BASE_URL`, `PHONE_NUMBER`) with actual values obtained from Safaricom developer portal.
- Ensure Ngrok is used to expose a public URL for `BASE_URL` during testing.
