NIVARCH – PHONE APP
===================
This folder is the phone version of Nivarch. It uses the same encrypted archive
as the PC program (the OneDrive folder "Nivarch"). The assistant runs on the phone
itself; nothing is sent to any AI service.

Start the PC program once first, so the "Nivarch" folder exists in OneDrive.
One-time setup, about 20 minutes.


STEP 1 – Put the app online (GitHub Pages, free)
-------------------------------------------------
1. Create a free account at https://github.com (skip if you have one).
2. Click "+" (top right) → "New repository".
   Name: pick something neutral that doesn't reveal what it is, e.g. "nv-app".
   Choose "Public" → "Create repository".
3. Click "uploading an existing file", drag in ALL files from this folder
   (not the folder itself) and click "Commit changes".
4. Go to "Settings" → "Pages". Under "Branch" choose "main" and "/ (root)" → "Save".
5. After a minute the address appears at the top, e.g.
       https://YOUR-USERNAME.github.io/nv-app/
   Write it down, including the slash at the end.

Only the program code is on GitHub – never your records. The page also asks
search engines not to list it.


STEP 2 – Let the app use your OneDrive (Microsoft, free)
---------------------------------------------------------
Microsoft requires apps to be registered in a "directory". The simplest way:
1. Go to https://azure.microsoft.com/free and create a free Azure account with the
   SAME Microsoft account as your OneDrive. Microsoft asks for a credit card to
   verify who you are; registering the app is free.
2. In https://portal.azure.com search for "App registrations" → "New registration".
   - Name: Nivarch
   - Supported account types: choose the one that includes "personal Microsoft accounts".
   - Redirect URI: choose "Single-page application (SPA)" and paste the address
     from step 1 (with the slash at the end).
   - Click "Register".
3. Copy the "Application (client) ID" (looks like xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx).


STEP 3 – Open it on your phone
------------------------------
1. Open the address from step 1 in Safari (iPhone) or Chrome (Android).
2. Paste the client ID and tap "Sign in with Microsoft". Allow access to your files.
3. Sign in to Nivarch with your password.
4. Add it to the home screen:
   - iPhone: Share → "Add to Home Screen".
   - Android: ⋮ menu → "Install app" / "Add to Home screen".


GOOD TO KNOW
------------
- The phone needs internet, because the archive is read from OneDrive.
- If you edit the same record on PC and phone at the same time, the latest save wins.
- Attachments: max 100 MB per file. Upload large files on Wi-Fi.
- Microsoft sign-in expires after a while without use – just sign in again.
- To remove the link to OneDrive on the phone: tap "Unlink OneDrive" at the bottom.

Font: Inter (SIL Open Font License 1.1, © The Inter Project Authors) is built in, so nothing is loaded from Google.
