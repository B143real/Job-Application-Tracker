# Job Application Tracker

## Project Vision
The Job Application Tracker is a user-centric, single-page web application designed to simplify job search management for users by enabling them to efficiently track, organize, and prioritize their job applications. It provides a streamlined and interactive solution to improve productivity and decision-making during the job search process. 

This tool reduces the stress of job hunting by consolidating all application details in one place, making progress tracking intuitive and user-friendly.

---

## Background
Job seekers often face challenges in staying organized during their job search. Tracking multiple applications across different platforms can lead to missed deadlines and opportunities. The Job Application Tracker was conceptualized to address these organizational challenges and create a centralized platform for managing job applications.

During a Peer-Assisted Learning (PAL) session on **November 27, 2024**, this idea was validated by peers and mentors, who recognized its relevance and potential impact. Key feedback from the session emphasized the importance of:
- Implementing intuitive filtering and search functionalities to quickly locate applications based on specific criteria.
- Adding a visual progress tracker to help users gauge their application stages at a glance.
- Prioritizing clarity and simplicity in the initial prototype to ensure usability for a wide audience.

This feedback shaped the design and development process, ensuring the tool meets user needs and serves as an innovative solution to real-world job application challenges.

---

## Features
### **Core Functionalities**
1. Add, edit, and delete job applications.
2. View job application details in a table format.
3. Filter or search applications by criteria such as:
   - **Status:** Applied, Interview Scheduled, Offer Received, Rejected.
   - **Company** or **Date Applied**.
4. Persistent data storage using `localStorage`.
5. Track application progress visually using a progress bar.
6. Select **Date Applied** using a calendar picker for consistent date input.
7. **Form Validation:**
   - Ensures users complete required fields (e.g., "Job Title," "Company," "Status," and "Date Applied") before submission using HTML5's `required` attribute.

---

## Technologies Used
- **HTML:** Structure of the web page.
- **CSS:** Styling for a clean and user-friendly layout.
- **JavaScript:** Interactivity, data handling, and local storage integration.
- **PlantUML:** For system diagrams like Use Case, Class, and Sequence Diagrams.

---

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/B143real/job-application-tracker.git
   ```
2. **Open the Application:**
   - Navigate to the project folder.
   - Open `index.html` in your browser to view the application.

3. **Test the Features:**
   - Add, edit, delete, and filter job applications.
   - View the progress bar for application tracking.
   - Select application dates using the calendar picker.
   - Experience built-in form validation for required fields.
   - Data is saved persistently using `localStorage`.

---

## Sprint Planning and Progress
### **Sprint 1 (Dec 5 – Dec 18, 2024)**
- **Goal:** Establish the project foundation.
- **Completed:**
  - Created GitHub repository and initial project structure.
  - Drafted initial Use Case and Class diagrams.
  - Incorporated feedback from the PAL session into project goals.

### **Sprint 2 (Dec 19 – Jan 1, 2025)**
- **Goal:** Build a basic prototype.
- **Completed:**
  - Developed HTML and CSS structure for the application.
  - Implemented add and edit functionalities using JavaScript.
  - Initiated filtering functionality and integrated local storage.

### **Sprint 3 (Jan 2 – Jan 12, 2025)**
- **Goal:** Refine and enhance the prototype.
- **Completed:**
  - Completed filtering functionality for searching by status and other criteria.
  - Integrated progress tracking visuals using a dynamic progress bar.
  - Enhanced the UI for clarity and interactivity.
  - Finalized and annotated Use Case, Class, and Sequence diagrams.

---

## Challenges and Solutions
### **Challenges:**
1. Ensuring data persistence without a backend.
2. Debugging filtering logic for complex user inputs.
3. Designing an intuitive and visually appealing UI.

### **Solutions:**
1. Used browser `localStorage` for lightweight and reliable data persistence.
2. Conducted iterative testing with mock data to validate filtering logic.
3. Enhanced the layout and functionality with CSS for a single-page application.

---

## Next Steps
1. Refine and test all implemented features to ensure seamless functionality.
2. Finalize design documentation to align with project implementation.
3. Record and prepare the interim video submission for January 2025.
4. Incorporate feedback from the interim submission into further improvements.
5. Prepare for the final presentation in May 2025, ensuring compliance with the single-page application requirement.

---

*This README will continue to be updated as the project progresses.*

