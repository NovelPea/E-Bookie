# E-Bookie

E-Bookie is a browser-based writing space for creating books, drafting chapters, and organizing your personal bookshelf. It runs as a single HTML file and stores demo data in the browser.

## Features

- **Account screens:** Sign up and log in with a local demo account.
- **Dedicated book setup screen:** Enter a title, genre, book type, description, and private planning notes.
- **Manuscript editor:** Write chapters, rename them, reorder them, add new chapters, and delete chapters.
- **Autosave settings:** Choose automatic saving or save manuscripts manually.
- **Bookshelf:** Search, sort, and filter your books.
- **Reading view:** Open a book and read its chapters.
- **Book deletion:** Delete a book and its manuscript after confirmation.
- **Settings:** Update your pen name, email, and bio; customize appearance, manuscript text size, sorting, and writing preferences.
- **Account deletion:** Permanently remove the local demo account and its books.
- **Responsive layout:** Works on desktop and mobile screens.

## Run the app

1. Save the app HTML as `index.html`.
2. Open `index.html` in a modern web browser.
3. Choose **Sign up** to create a local demo account, or log in to an existing account in that browser.

No build tools or server are required.

## Creating and writing a book

1. Select **Create a book** on the bookshelf.
2. Enter book details and select **Continue to manuscript**.
3. Write in the chapter editor. Use **+** to add chapters.
4. Select **Save** to save manually. If autosave is enabled, edits are saved automatically.
5. Close the editor to return to the bookshelf.

## Data and privacy

This is a front-end demo. Accounts, settings, books, and manuscripts are stored in the browser’s `localStorage`. They are not uploaded, synced between devices, or protected by a server. Clearing browser data removes the saved information.

The demo account flow is **not suitable for real credentials or sensitive personal information**. Passwords are stored locally as plain text; do not use a real password.

## Limitations

- There is no backend, cloud sync, or multi-device account access.
- There is no server-side authentication or recovery.
- Data is only available in the browser profile where it was created.
- Account deletion removes locally stored account and book data for that account.
