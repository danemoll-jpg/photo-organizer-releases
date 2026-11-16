# Photo Organizer — releases

Download builds of **Photo Organizer** (Windows) here. Each release has:

- `PhotoOrganizer-<version>-windows.zip` — the full download. Extract anywhere you can write to and run `PhotoOrganizer.exe`.
- `PhotoOrganizer-app-<version>.zip` and `update-manifest.json` — used by the app's built-in updater (Dashboard → Updates). You don't need to download these by hand.

The app is not code-signed, so Windows may show "Windows protected your PC": choose **More info → Run anyway**.

Your settings and library data live in `%LOCALAPPDATA%\PhotoOrganizer`, outside the install folder, so updating never touches them. The first run is a safe dry run: nothing is moved until you turn `dry_run` off.
