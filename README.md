# All-songs-of-your-favorite-artist
Instructions:

Sign up for a Genius account:
Go to the Genius website and create a free account if you don't have one already.
You'll need to provide a nickname (one word), email address, and password.

Access the API Clients page:
Navigate to https://genius.com/api-clients

Create a new API client:
Click on the "New API Client" button.
Fill out the required information:
App Name and
App Website URL (you can use a placeholder if needed, e.g. https://example.com).

Generate the access token:
After saving your new API client, you'll see a "Client ID" and "Client Secret".
Click on "Generate Access Token" to create your Client Access Token.

Store your access token securely:
Copy the generated Client Access Token.
Keep it confidential and don't share it publicly.

Use the access token in your API requests:
Include the token in the Authorization header of your API requests. (Line 6 of the code!)

After you download the python script and include the token, run the script and write the artist's name when prompted. For best results visit the artist's genius page and copy paste the name right below their profile picture.
