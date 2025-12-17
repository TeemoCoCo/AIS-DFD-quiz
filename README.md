# DFD Labeling Quiz – Expenditure & Revenue Cycles

An interactive web-based quiz for students to practice labeling missing parts in Data Flow Diagrams (DFD) for Accounting Information Systems.

This quiz covers 8 diagrams from the Expenditure Cycle and Revenue Cycle, with automatic checking, immediate feedback, and forgiving answer matching (ignores case and spaces).

## Features
- 8 interactive DFD diagrams with missing labels (A, B, C, ..., a, b, ...)
- Case-insensitive and space-insensitive answer checking (e.g., "sales order", "SalesOrder", "sales  order" all accepted)
- Handles interchangeable answers (e.g., packing slip and bill of lading can be swapped where applicable)
- After submission:
  - Shows correct/incorrect for each label
  - Displays total score
  - Buttons: Previous Diagram ← | Retry This Diagram | Next Diagram → (or Back to Home on the last diagram)
- Clean, responsive design (works on desktop and mobile)
- Fully offline-capable (no server needed once hosted)

## Diagrams Included
1. Expenditure Cycle DFD Level 0
2. Expenditure Cycle DFD Level 1: Ordering
3. Expenditure Cycle DFD Level 1: Receiving
4. Expenditure Cycle DFD Level 1: Cash Disbursement
5. Revenue Cycle DFD Level 0
6. Revenue Cycle DFD Level 1: Sales Order Entry
7. Revenue Cycle DFD Level 1: Shipping
8. Revenue Cycle DFD Level 1: Billing

## How to Use (For Students)
1. Open the website.
2. Click on any diagram to start.
3. Fill in the missing labels.
4. Click "Submit Answers" to check your work.
5. Use "Retry" to try again, "Previous/Next" to navigate, or "Back to Home" to return to the list.

## File Structure
your-project-folder/
├── index.html          ← Main quiz file (open this in browser)
├── README.md           ← This file
└── diagrams/           ← Folder containing the 7 diagram images
├── EXP 1.0 A.png
├── EXP 1.1 A.png
├── EXP 2.1 A.png
├── EXP 4.1 A.png
├── REV 1.0 A.png
├── REV 1.1 A.png
├── REV 2.1 A.png
└── REV 3.1 A.png

## How to Run Locally
1. Download or clone this repository.
2. Place all files exactly as shown above.
3. Open `index.html` in any web browser (Chrome, Firefox, etc.).
   - No internet required after loading!

## How to Host Online (Free Options)
### Recommended: GitHub Pages
1. Create a GitHub account at https://github.com
2. Create a new public repository.
3. Upload `index.html`, the `diagrams` folder, and this `README.md`.
4. Go to Settings → Pages → Set source to "main" branch / root folder.
5. Your quiz will be live at: `https://yourusername.github.io/your-repo-name/`

## For Teachers/Instructors
- Fully client-side — no data collected, no login required.
- Easy to customize: edit correct answers directly in the JavaScript section of `index.html`.
- Share the link with students via email, LMS (Moodle, Google Classroom), or QR code.

## License
Free to use, modify, and distribute for educational purposes.

---
Created with ❤️ for Accounting Information Systems students.
