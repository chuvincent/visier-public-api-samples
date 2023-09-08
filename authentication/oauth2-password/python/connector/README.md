# Python Connector Password Grant Authentication
1. Create a virtual environment: `python3 -m venv env`.
1. Activate the virtual environment: `source env/bin/activate`.
1. Install the required dependencies: `pip install -r requirements.txt`.
1. Clone the `../.env-password-template` environment file to `.env`.
1. Update `.env` file with the appropriate values to match your system details.
1. Source the environment file: `source .env` and provide the sensitive values (which should not be stored in the file itself).
1. Call `python app.py` to see a simple example of how to parse the JWT and make a simple Model API call.
1. Deactivate the virtual environment: `deactivate`.