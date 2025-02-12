

# Job Application Tracker

## Project Vision
The **Job Application Tracker** is a user-centric, single-page web application designed to simplify job search management for users by enabling them to efficiently track, organize, and prioritize their job applications. It provides a streamlined and interactive solution to improve productivity and decision-making during the job search process.

This tool reduces the stress of job hunting by consolidating all application details in one place, making progress tracking intuitive and user-friendly.

---

## Background
Job seekers often face challenges in staying organized during their job search. Tracking multiple applications across different platforms can lead to missed deadlines and opportunities. The **Job Application Tracker** was conceptualized to address these organizational challenges and create a centralized platform for managing job applications.

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
   - **Status**: Applied, Interview Scheduled, Offer Received, Rejected.
   - **Company** or **Date Applied**.
4. Persistent data storage using **localStorage**.
5. Track application progress visually using a progress bar.
6. Select **Date Applied** using a calendar picker for consistent date input.
7. **Form Validation**:
   - Ensures users complete required fields (e.g., "Job Title," "Company," "Status," and "Date Applied") before submission using HTML5's `required` attribute.
8. **Multi-Language Support**: Switch between English, Spanish, and French with dynamically updated interface text.
9. **Dark Mode**: Toggle between light and dark themes for better user experience.
10. **Settings Panel**: Customize preferences like theme, language, and notifications, with settings saved persistently using **localStorage**.

---

## Technologies Used
- **HTML**: Structure of the web page.
- **CSS**: Styling for a clean and user-friendly layout.
- **JavaScript**: Interactivity, data handling, and local storage integration.
- **localStorage**: For saving and persisting user settings (theme, language, and notifications).
- **Font Awesome**: For icons.
- **Chart.js**: For visualizing job application data (optional, if used).

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
   - Switch between languages (English, Spanish, French).
   - Toggle between light and dark themes.
   - Modify settings like language, theme, and notifications in the settings panel.

---

## Sprint Planning and Progress

### **Sprint 1 (Dec 5 – Dec 18, 2024)**
- **Goal**: Establish the project foundation.
- **Completed**:
  - Created GitHub repository and initial project structure.
  - Drafted initial Use Case and Class diagrams.
  - Incorporated feedback from the PAL session into project goals.

### **Sprint 2 (Dec 19 – Jan 1, 2025)**
- **Goal**: Build a basic prototype.
- **Completed**:
  - Developed HTML and CSS structure for the application.
  - Implemented add and edit functionalities using JavaScript.
  - Initiated filtering functionality and integrated local storage.

### **Sprint 3 (Jan 2 – Jan 12, 2025)**
- **Goal**: Refine and enhance the prototype.
- **Completed**:
  - Completed filtering functionality for searching by status and other criteria.
  - Integrated progress tracking visuals using a dynamic progress bar.
  - Enhanced the UI for clarity and interactivity.
  - Finalized and annotated Use Case, Class, and Sequence diagrams.

### **Sprint 4 (Jan 13 – Jan 26, 2025)**
- **Goal**: Implement multi-language support, dark mode toggle, and settings panel.
- **Completed**:
  - **Multi-Language Support**: Added functionality to switch between English, Spanish, and French.
  - **Dark Mode**: Implemented a theme toggle to switch between light and dark modes.
  - **Settings Panel**: Created a settings section for users to adjust theme, language, and notifications preferences.
  - **LocalStorage Persistence**: Ensured that user settings (theme, language, notifications) are saved and persist across sessions.

### **Sprint 5 (Jan 26 – Feb 9, 2025)**
- **Goal**: Refine and finalize the application.
- **Completed**:
  1. **Refine User Interface and Experience:**
     - Polished the design and interactions for a smoother user experience.
     - Implemented final UI adjustments based on user feedback and testing.
     - Ensured the app is responsive across all devices and screen sizes.

  2. **Implement Application Security Features:**
     - Added necessary **input validation** and **security measures** to protect against invalid data entry.
     - Enhanced the **privacy mode** settings to provide better data handling and protection for users.

  3. **Testing and Bug Fixing:**
     - Performed thorough testing of all features to ensure stability and smooth functionality.
     - Tested the settings panel, multi-language switching, and dark mode toggle thoroughly.

  4. **Integrate User Feedback:**
     - Gathered feedback from peers or instructors and integrated relevant suggestions or improvements into the app.
     - Implemented a simulation of user authentication or other security measures for securing job data .

  5. **Finalize LocalStorage and Data Management:**
     - Ensured all data (like job applications, preferences, etc.) are correctly stored and retrieved from localStorage.

---

## Challenges and Solutions

### **Challenges:**
1. Ensuring data persistence without a backend.
2. Debugging filtering logic for complex user inputs.
3. Designing an intuitive and visually appealing UI with multi-language and theme toggle functionality.
4. Making sure while css was in a diferent file the website still runned on the live server
5. Improving the layout 

### **Solutions:**
1. Used browser **localStorage** for lightweight and reliable data persistence.
2. Conducted iterative testing with mock data to validate filtering logic.
3. Enhanced the layout and functionality with **CSS** for a single-page application and ensured clarity across multiple languages and themes.

---
NEXT STEPS (Sprint 6)
1. Display appplication tables properly
2. Decide between the functionality of private mode
3. Display graphical stats on the dasboard section 
4. Improve user authentication Login/Register simulation as its a SPA project
5. improve the text box input

*This README will continue to be updated as the project progresses.*
```

