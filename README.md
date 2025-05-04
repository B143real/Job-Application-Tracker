# Job Application Tracker

## Project Vision

The Job Application Tracker is a user-centric, single-page web application designed to simplify job search management for users by enabling them to efficiently track, organize, and prioritize their job applications. It provides a streamlined and interactive solution to improve productivity and decision-making during the job search process.

This tool reduces the stress of job hunting by consolidating all application details in one place, making progress tracking intuitive and user-friendly.

## Background

Job seekers often face challenges in staying organized during their job search. Tracking multiple applications across different platforms can lead to missed deadlines and opportunities. The Job Application Tracker was conceptualized to address these organizational challenges and create a centralized platform for managing job applications.

During a Peer-Assisted Learning (PAL) session on November 27, 2024, this idea was validated by peers and mentors, who recognized its relevance and potential impact. Key feedback from the session emphasized:

- The importance of intuitive, visual progress tracking so users can quickly gauge the stage of each application.
- Prioritizing clarity and simplicity in the prototype to ensure usability for a wide audience.

This feedback shaped the design and development process, ensuring the tool meets user needs and serves as an innovative solution to real-world job application challenges.

---

## Features

- **Add, Edit, and Delete Job Applications:** Create new applications, update details, or remove records as required.
- **View Applications in a Table:** All job applications are displayed in a structured, easy-to-read table.
- **Visual Progress Tracking:** Applications display a progress bar and status indicator (e.g., "Applied," "Interview Scheduled," etc.) to help users track their progress at a glance.
- **Chart.js Dashboard:** The dashboard uses Chart.js to show analytics and counts (Total, Pending, Accepted, Rejected applications) as a bar chart.
- **Date Input/Calendar Picker:** Select application dates via a calendar input for accuracy and consistency.
- **Persistent localStorage:** All application data and user preferences (theme/language) are automatically saved on the user’s own device for privacy.
- **Multi-Language Support:** Instantly switch between English, Spanish, and French.
- **Dark Mode:** Users can toggle between light and dark themes for accessibility and personal preference.
- **Form Validation:** Required fields such as Job Title, Company, Status, and Date Applied must be filled in for any job entry to be accepted.
- **Modern UI:** Uses Font Awesome icons and Google Fonts for a professional look.

> **Note:**  
> Filtering and search were originally planned, but were removed prior to release to maximize app stability and reliability for users. See “Reflection and Trade-offs” below.

---

## Technologies Used

- **HTML, CSS:** For page structure and responsive, accessible layout
- **JavaScript:** Handles interactivity, CRUD logic, and localStorage integration
- **localStorage:** Retains jobs and preferences on the client device
- **Font Awesome:** For user interface icons
- **Chart.js:** Elegant analytics bar chart
- **Google Fonts:** Typography

---

## How to Run the Project

1. **Clone the Repository:**
   ```
   git clone https://github.com/B143real/job-application-tracker.git
   ```
2. **Open the Application:**
   - Go to the cloned project folder.
   - Open `index.html` in your browser (no installation needed).

3. **Try the Features:**
   - Add, edit, and delete job applications.
   - Track progress with visual status bars.
   - Use the calendar date input for application dates.
   - Switch easily between English, Spanish, and French.
   - Toggle between light and dark themes.
   - View your application analytics on the dashboard.
   - All information and preferences are saved to your browser only.

---

## Sprint Planning and Progress

- **Sprint 1:** Setup repo, gathered requirements, created initial wireframes and diagrams, reviewed peer/mentor feedback.
- **Sprint 2:** Developed HTML/CSS skeleton, implemented application add/edit/delete logic, set up localStorage.
- **Sprint 3:** Integrated progress bars and status visualization, completed app table, finalized diagrams.
- **Sprint 4:** Added multi-language, dark mode, and settings panel. Ensured theme and language are persistent in localStorage.
- **Sprint 5:** Refined UI/UX, improved input validation, enhanced responsiveness, finalized analytics dashboard with Chart.js.
- **Sprint 6:** UI/UX polishing, optimized code, removed unnecessary settings, and finalized all core features.

---

## Reflection and Trade-Offs

Filtering and search capabilities were originally part of the plan. However, after encountering persistent bugs and instability, I decided to remove these features before release to ensure the core functionality remained robust, reliable, and user-friendly. This design decision allowed me to focus on the stability and quality of essential features such as adding, editing, deleting, and tracking applications, as well as settings, analytics, and language support.

This experience reinforced the importance of focusing on software quality and making Agile trade-offs when necessary—delivering features that work well, rather than features that might compromise the user experience.

---

## Challenges and Solutions

- **Ensuring Reliability Without Backend:** Used localStorage exclusively for persistence and privacy.
- **Feature Prioritization:** Focused on robust CRUD and visual progress after removing filtering.
- **Multi-Language & Theme Support:** Updated all interface text/site-wide in three languages but
- **User Validation & Feedback:** Required all critical fields for job applications and based refinements on test feedback.
- **UI Responsiveness:** Tested and refined layout for desktop and mobile browsers.

---



**GitHub Repository:**  
https://github.com/B143real/job-application-tracker

---

*This README will be updated as the project or documentation evolves. The final submitted version accurately reflects the app’s current capabilities and design decisions.*

---

