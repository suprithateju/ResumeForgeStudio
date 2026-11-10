ResumeForge Studio 📄✨

Project : Resume Builder (Section A: Web Tools)

A privacy-first, offline-capable resume creation studio built with pure web technologies. Create, format, reorder, preview, and export high-standard ATS resumes directly from your browser with zero logins, cloud tracking, or hidden paywalls.

🎯 The Problem & Vision

"A company opens applications today. The resume site lets you fill in everything, then asks you to pay to download it. Build a resume maker that is yours, free, and keeps your details on your device."

Most online resume builders trap your data behind paywalls right when you click "Download," or leak personal information to remote servers. ResumeForge Studio is engineered to be 100% client-side, self-contained, and completely offline-ready.

✨ Features

Live Dual-Column Data Entry: Inputs are organized into two clean, balanced panes (Personal/Skills on the left, Experience/Education on the right) for an efficient desktop editing experience.

Dedicated Review & Inspection Modal: Inspect your exact A4 page layout with fluid zoom controls (Fit Width, 100%, +, -) before exporting.

3 Distinct Visual Templates:

Classic Ivy League: Traditional ATS centered header with horizontal rules and structured typography.

Modern Tech Sidebar: Dual-column layout with an accent sidebar for contact chips and skill pills.

Contemporary Minimal: Left monogram badge, compact metadata tags, and a 2-column card grid for portfolio projects.

Native HTML5 Drag-and-Drop Reordering: Easily rearrange sections (Experience, Education, Projects, Skills, Summary, Certifications) to prioritize your strongest assets.

Selectable & Searchable Vector PDF Export: Uses @media print and the browser's native print engine (window.print()). Unlike canvas-screenshot tools, all text remains copyable, searchable (Ctrl+F), and ATS-readable.

Local File Save & Restore: Export your resume data to a .json backup file with one click and load it back at any time.

Continuous Auto-Save: Automatically persists your edits in browser localStorage.

Live ATS Completeness Score: Real-time feedback bar analyzing resume detail depth and keyword strength.

Zero External Dependencies: Built without third-party CDNs, external web fonts, or server APIs—runs safely with your internet turned off.


🚀 Quick Start

Run Locally

Since this project has no build steps or dependencies:

Clone the repository:

git clone https://github.com/suprithateju/ResumeForgeStudio.git


Navigate into the folder:

cd ResumeForgeStudio


Open index.html in any modern web browser:

On Windows: Double-click index.html or run start index.html

On Mac: Run open index.html

On Linux: Run xdg-open index.html

How to Export to PDF

Fill out your details or click Sample Data for a quick demonstration.

Click Review Resume to inspect the layout, or click Export PDF directly.

In your browser's Print window:

Destination: Select Save as PDF

Paper Size: Select A4

Margins: Select None or Default

Check Background graphics to preserve colors and accent bars.

🛠️ Project Structure

ResumeForgeStudio/
├── index.html       # Standalone SPA (HTML structure, CSS styles, JS state engine)
├── README.md        # Project overview and documentation
└── LICENSE          # MIT License


🔒 Privacy & Data Ownership

No accounts or logins required.

No remote telemetry or analytics trackers.

Your resume content never leaves your computer.

📄 License

Distributed under the MIT License.
