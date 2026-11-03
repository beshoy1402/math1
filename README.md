# KHALED MATH

Teacher only grade management portal for Mr. Khaled.

## Classes
- G12A — AP Calculus
- G12B, G12C, G12D — Advanced Math

## Features
- Teacher sign in with Firebase Authentication; Firestore stores class data.
- Add, edit, move, and delete students.
- Quick grade adjustments, student grade history, and undo.
- Day by day Participation (15), Attendance (10), Homework (10), Quizzes (15), and Behavior (5) marks.
- Class reports exported as CSV for Excel or printed/saved as PDF.
- Attendance, homework, exams, groups, analytics, dark mode, and responsive mobile navigation.
- Password protected Delete Data action.

## Run locally
Open `index.html` in a modern browser. The site loads Firebase web SDK modules from Google's CDN and uses the project settings in the page. Firestore security rules are in `firestore.rules`.

## GitHub Pages
In repository Settings → Pages, choose GitHub Actions as the deployment source. The included workflow deploys pushes to `main`.
