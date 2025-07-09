This script converts excel files into google sheets. This is used for large conversions that are typically over 50K lines when google starts to get upset.

1. Setup a google cloud account (free) and create a new "project".
2. click on APIs and Services and go to the "Credentials" section.
3. At the top, click "+ Create credentials" and generate a "Service Account".
4. Basic permissions is okay.
5. Click on the Service and then go to "Keys", once here click "Add key" and "Create new key".
6. Generate a JSON file then copy the content and paste it into "google-credentials.json" in the dir.
7. In your end-point google sheet, share it with the Service Accounts email address.
8. Run the script and provide excel file path, google sheet name, and columns with dates.
9. You're finished!