Accounting Information Systems – DFD Labeling Practice & Past Exams
An interactive, fully offline-capable web application for students to practice labeling Data Flow Diagrams (DFD) from both regular exercises and real past exam questions.
The site features two separate sections:

DFD Labeling Practice – Standard textbook-style DFD diagrams
Past Exam DFD Labeling – Actual DFD questions from previous exams (2015–2025)

Features

Clean two-column layout: diagram on the left, answer inputs on the right
Responsive design – works perfectly on desktop, tablet, and mobile
Student-friendly answer checking:
Case-insensitive
Space-insensitive
Plural tolerance (e.g., "Packing slip" = "Packing slips")
Multiple accepted answers per label (e.g., "cheque"/"check")
Interchangeable pairs fully supported (even with plural/singular variations)

Immediate feedback with score
Navigation: Previous / Next / Retry / Back to List
Top navigation menu to switch between Practice and Past Exams
Clicking a nav link shows only that section for focused practice
All images stored in separate folders for easy organization

Folder Structure
your-project-folder/
├── index.html                  ← Main file (this one)
├── README.md                   ← This file
└── diagrams/
    ├── practice/               ← Regular practice diagrams
    │   ├── EXP 1.0 A.png
    │   ├── EXP 1.1 A.png
    │   ├── EXP 2.1 A.png
    │   ├── EXP 4.1 A.png
    │   ├── REV 1.0 A.png
    │   ├── REV 1.1 A.png
    │   ├── REV 2.1 A.png
    │   └── REV 3.1 A.png
    └── past paper/             ← Past exam diagrams
        ├── 1516SEM2_Q1d.png
        ├── 1819SEM1_Q2a.png
        ├── 2223SEM1_Q1a.png
        ├── 2223SEM1_Q2a.png
        ├── 2223SEM2_Q1a.png
        ├── 2223SEM2_Q2a.png
        └── 2425SEM1_Q2a.png

How to Use (For Students)

Open index.html in any web browser (no internet needed after loading).
Use the top navigation to choose:
DFD Labeling Practice – for regular exercises
Past Exam DFD Labeling – for real exam-style questions

Click any diagram card to start labeling.
Type answers in the right column.
Click Submit Answers to check your work.
Use Previous/Next to navigate, Retry to try again, or Back to List to return.

How to Run Locally

Download or clone this repository.
Ensure the folder structure above is maintained (especially the diagrams subfolders).
Double-click index.html or open it in your browser.

How to Host Online (Free & Easy)
GitHub Pages (Recommended)

Create a free GitHub account.
Create a new public repository.
Upload index.html, README.md, and the entire diagrams folder.
Go to Settings → Pages → Set source to "main" branch / root.
Your site will be live at: https://yourusername.github.io/your-repo-name/

Other free options: Netlify, Vercel, Cloudflare Pages (all support drag-and-drop or GitHub connect).
For Teachers / Customization

Add new diagrams by editing the practiceDiagrams or pastDiagrams arrays in the <script> section.
Support for multiple correct answers: use arrays, e.g., ["Cheque", "Check"]
Easily change titles, labels, or add interchangeable pairs.
No backend or database needed – pure HTML/CSS/JS.

License
Free for educational use. Feel free to modify and share with your students.

Created for Accounting Information Systems students – Happy practicing! 🚀
