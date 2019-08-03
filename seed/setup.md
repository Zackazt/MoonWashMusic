1. %ALBUM_IMAGE_NAME%
2. %RELEASE_TYPE%
  1. singles
  2. albums
  3. eps
3. %RELEASE_NAME%
  1. Capitalized - %RELEASE_NAME_C%
  2. Non-capitalized - %RELEASE_NAME_NC%
4. %ARTIST_NAME%
  * This will be parsed out from the title. The convention of (feat. Artist 1 & Artist 2) will easily allow me to do this.
5. Each platform link in the format of: %PLATOFORMNAME_LINK%

#### The user experience should be as follows:

  1. Enter an artist name.
  2. Select a release type.
  3. Enter a release name.
  4. Provide the links to each of the platorms to listen.
  5. Click submit.

#### The code will perform the following tasks:

  1. Provide a GUI for the user to enter the information.
  2. Send the information through an HTTP request.
  3. Flask server will accept the request and parse the information.
  4. Flask server will pass the information to a Python script that will parse through the seed html file and string replace the key words.
  5. Python script will create the files.
  6. Python script will commit the files to the GitHub repository.

#### Things left to ponder:
  1. YOur mother
