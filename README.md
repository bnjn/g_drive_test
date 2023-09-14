# g-drive-test
Saves a CSV file from Drive for use as an ingestion source in DataHub

# Setup
- Follow the environment setup in this guide: https://developers.google.com/drive/api/quickstart/python
- Rename the downloaded credentials json `credentials.json` and place it in `bin`
- Create a python venv if needed.
- Install dependencies: `pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`
- cd into `bin` and run `drive.py`