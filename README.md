# Arluee ♡ BeeBee — configured couple app

Your Firebase Web App configuration has been inserted into `index.html`.

## Finish setup
1. In Firebase Console for project `arluee-beebee`, enable **Authentication > Sign-in method > Anonymous**.
2. Create a **Cloud Firestore** database.
3. Install Node.js on a computer, then install Firebase CLI: `npm install -g firebase-tools`.
4. In a terminal, open this project folder and run:
   - `firebase login`
   - `firebase use --add` and select `arluee-beebee`
   - `firebase deploy`
5. Open the Firebase Hosting URL on both phones.
6. Arluee creates a room and shares the generated 8-character code privately. BeeBee joins with that code.

This version does not use Cloud Functions, so it avoids needing a paid Functions deployment. Firebase Authentication and Firestore still need to be enabled. Keep the room code private. Anonymous sign-in identifies a browser session, not a verified person.

## Features
- Private 2-member room, using an 8-character invitation code
- Live messages and love reactions while both users have the app open
- Mobile-friendly pink design and anniversary countdown to 16 November 2026

Not included yet: photo uploads, push notifications while the app is closed, account recovery, and end-to-end encryption.
