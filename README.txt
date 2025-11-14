AgriSmart Hub — Project Structure and Team Workflow

Team Members and Roles

No.	Name	Page / Role	Push Schedule	Connection to Main Branch
1	Bemnet	Project Lead / Home Page	3 pushes/day	Works directly on main branch at the start
2	Eyerusalem	About Page Developer	2 pushes/day	After Bemnet completes homepage navbar and footer
3	Feven	Services Page Developer	2 pushes/day	After homepage navbar is stable
4	Aman	Innovations Page Developer	2 pushes/day	Merge to main after Services page is merged
5	Muaz	Contact Page Developer	2 pushes/day	Merge to main after Innovations page is merged
6	Nahom	UI/UX Designer & CSS Specialist	3 pushes/day	Merge to main after all HTML pages are merged
Page Assignments and Responsibilities

Bemnet — index.html

Bootstrap navbar linking to all five pages.
Section with a background image and 'Join Now' button.
Three feature cards showing Smart Farming Tech, Market Access Platform, and Climate Advisory Services.
Footer with copyright and social media icons.
Eyerusalem — about.html

Two-column layout with image and text describing mission and vision.
Mission and Vision section with icons or cards.
Progress Bar showing goals achieved (e.g., 80% Farmer Digitalization Target).
Feven — services.html

Grid of six Bootstrap cards showing services like Smart Irrigation, Drone Mapping, Digital Marketplace, etc.
Each card has an image placeholder, short description, and 'Learn More' button.
Aman — innovations.html

Carousel displaying 3–5 innovation images with captions (Refer to W3Schools Bootstrap Carousel).
Optional: embed a YouTube video about smart farming technologies.
Muaz — contact.html

Bootstrap contact form with Name, Email, Subject, and Message fields.
Sidebar card with contact details (phone, email, address).
Embedded Google Map iframe showing office location.
Nahom — style.css

Use an external CSS file named 'style.css' for colors, fonts, and hover effects.
Use placeholder image names (e.g., image1.jpg, image2.jpg) in the HTML code.
Apply Bootstrap 5 via CDN.
Use soft green color scheme (#2e7d32, #81c784, #f1f8e9).
Submission Requirements

Folder name: AgriSmart_Hub
Files: index.html, about.html, services.html, innovations.html, contact.html, style.css
All links and pages must be functional locally (no server required).
Include a README.txt listing image placeholders used.
Zip the folder before submission.
Git Collaboration Instructions — AgriSmart Hub

Repository URL: https://github.com/Amex-0/AgriSmart_Hub-.git

Initial Setup (Do this once)
1. Clone the repository to your local computer
git clone https://github.com/Amex-0/AgriSmart_Hub-.git

2. Move into the project directory (if necessary)
cd AgriSmart_Hub-

3. View existing branches
git branch -a

4. Switch to main branch
git checkout main

5. Pull the latest code from main
git pull origin main

6. Switch to development branch
git checkout dev

7. Pull latest updates from main into dev
git pull origin main

Daily Workflow (Follow this order every time you work)
1. Make sure you are on dev branch
git checkout dev

2. Pull latest changes before starting work
git pull origin dev

3. Edit your assigned file only
Example:
Bemnet → index.html
Eyerusalem → about.html
Feven → services.html
Aman → innovations.html
Muaz → contact.html
Nahom → style.css
4. Stage your changes
git add <your_file_name>

5. Commit your changes with a clear message
git commit -m "Updated <your_file_name> section"

6. Pull again before pushing to avoid conflicts
git pull origin dev

7. Push your committed changes to dev branch
git push origin dev

Important Notes
Always work only on your assigned file.
Never make direct changes to main branch.
Always pull before you push.
If merge conflicts occur, resolve them locally before pushing.
Ensure your HTML and CSS files are functional and linked properly before pushing.
After everyone finishes, the team lead will merge dev into main.