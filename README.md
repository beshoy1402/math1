# KHALED MATH

Responsive grade-management portal for Mr. Khaled.

## Classes
- G12A — AP Calculus
- G12B, G12C, G12D — Advanced Math

## Features
- Add, edit, move, and delete students
- Quick +5 / -5 and custom grade adjustments
- Student grade history, undo, class statistics and analytics
- Weighted grade calculator, dark mode, responsive layout
- Student roster and grade history saved in this browser with localStorage

## Run locally
Open `index.html` in a modern browser. No build step or dependencies required.

## GitHub Pages
In repository Settings → Pages, choose GitHub Actions as the deployment source. The included workflow deploys every push to `main`.

## Data limitation
This version stores data only in the current browser on the current device. It does not sync between devices or include secure teacher authentication. Connect Firebase Authentication and Firestore before using real student records. The initial roster is sample data.
