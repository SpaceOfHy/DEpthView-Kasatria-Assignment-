============================================================
KASATRIA 3D DATA VISUALISATION - READ ME
============================================================

Project: DEpthView

------------------------------------------------------------
1. PROJECT OVERVIEW
------------------------------------------------------------

This project is an interactive 3D data visualisation website
developed using HTML, CSS, JavaScript and Three.js.

The application retrieves data from Google Sheets and displays
the data as interactive 3D objects.

The project provides four different visualisation layouts:

1. TABLE
2. SPHERE
3. HELIX
4. GRID

------------------------------------------------------------
2. HOW TO OPEN THE 3D VISUALISATION
------------------------------------------------------------

STEP 1:
Open the project folder.

STEP 2:
Locate the following file:

    index.html

STEP 3:
Run the project using a local web server.

For example, if using Visual Studio Code:

    1. Install the "Live Server" extension.
    2. Right-click index.html.
    3. Select "Open with Live Server".

The website will then open in your web browser.

IMPORTANT:
Do NOT simply open index.html using "file://".
Google OAuth and Google APIs require the website to run
through a web server.


------------------------------------------------------------
3. GOOGLE SIGN-IN
------------------------------------------------------------

When the website opens, a welcome screen will appear.

Click:

    "Sign in with Google"

Select a Google account and complete the Google
authentication process.

After successful authentication, the application will
request permission to access the Google Sheet.

Click:

    "Authorize Google Sheets"

After authorization, the application will load the data
from Google Sheets.


------------------------------------------------------------
4. VIEWING THE 3D VISUALISATION
------------------------------------------------------------

After the Google Sheet has successfully loaded, the 3D
visualisation will appear.

The application will initially display the data in:

    TABLE

At the bottom of the page, four buttons are available:

    TABLE
    SPHERE
    HELIX
    GRID

Click any button to change the arrangement of the data.


------------------------------------------------------------
5. 3D CONTROLS
------------------------------------------------------------

The visualisation can be controlled using the mouse.

ROTATE:
    Click and drag the mouse.

ZOOM:
    Use the mouse scroll wheel.

PAN:
    Use the appropriate mouse interaction supported by
    TrackballControls.


------------------------------------------------------------
6. DATA DISPLAY
------------------------------------------------------------

Each data record is displayed as a 3D information card.

The card contains:

    - Name
    - Photo
    - Age
    - Country
    - Interest
    - Net Worth

The background colour of each card represents the person's
net worth:

    RED
        Net worth below $100,000

    ORANGE
        Net worth from $100,000 to $200,000

    GREEN
        Net worth above $200,000


------------------------------------------------------------
7. GOOGLE SHEETS
------------------------------------------------------------

The visualisation obtains its data from the configured
Google Spreadsheet.

The application reads the following columns:

    Column A - Name
    Column B - Photo
    Column C - Age
    Column D - Country
    Column E - Interest
    Column F - Net Worth

If the Google Sheet cannot be loaded, check:

    1. Google API configuration.
    2. OAuth Client ID.
    3. API Key.
    4. Google Sheets API.
    5. Spreadsheet ID.
    6. Spreadsheet permissions.
    7. OAuth authorization settings.


------------------------------------------------------------
8. SIGN OUT
------------------------------------------------------------

After the data has been loaded, a "Sign Out" button will
appear.

Click "Sign Out" to:

    - Revoke the Google Sheets access token.
    - Remove the loaded 3D data.
    - Hide the visualisation.
    - Return to the Google Sign-In screen.


------------------------------------------------------------
9. PROJECT FILES
------------------------------------------------------------

The main files included in this project are:

    index.html
        Main webpage and 3D visualisation.

    privacy.html
        Privacy Policy page.

    terms.html
        Terms of Service page.

    READ_ME.txt
        Project instructions and usage guide.


------------------------------------------------------------
10. REQUIREMENTS
------------------------------------------------------------

The application requires:

    - A modern web browser
    - Internet connection
    - A valid Google account
    - Google OAuth authentication
    - Access to the configured Google Spreadsheet

Recommended browsers:

    - Google Chrome
    - Microsoft Edge
    - Mozilla Firefox

------------------------------------------------------------
11. PRIVACY POLICY AND TERMS OF SERVICE
------------------------------------------------------------

The website provides links to:

    Privacy Policy
    Terms of Service

These pages can be accessed from the footer at the bottom
of the website.

------------------------------------------------------------
END OF READ ME
------------------------------------------------------------