# Product Requirements Document (PRD)

## Project Name
*Notebook*

## 1. Overview
This project is a **minimal markdown note-taking web app** designed to make note organization simpler than Notion. It focuses on offering a cozy, nostalgic writing experience — like writing in a real notebook — while keeping features minimal and intuitive.

## 2. Goals & Objectives
- Provide a clean, distraction-free space for writing and organizing notes.  
- Simplify note management with intuitive folder structure and drag-and-drop organization.  
- Offer instant markdown preview for writers who want formatting without clutter.  
- Maintain a familiar, notebook-like atmosphere through a minimal black-and-white aesthetic.

## 3. Target Audience
General users who want a **simple, minimal, and cozy** note-taking experience — free from the overwhelming complexity of traditional productivity tools.

## 4. Core Features (MVP)

### A. Authentication
- Login and registration with name, email, and password.  
- Store user data securely on the server.

### B. Home Page (Notes Dashboard)
- Display all user notes as boxes showing:
  - Title  
  - First 100 words  
  - Last updated time  
- Folder functionality:
  - Create new folders (button at top left)  
  - Rename or delete folders  
  - Drag and drop notes into/out of folders  
- “Create Note” button (top left) for new note creation.

### C. Editing Page (Note Editor)
- Two-pane layout:
  - **Left:** Plain text editor for writing.  
  - **Right:** Live markdown preview, updating in real time.  
- Auto-save notes as the user types.  
- “Delete” button (bottom right) with confirmation popup.

### D. Login Page
- Simple form with fields for:
  - Name  
  - Email  
  - Password  
- Black-and-white design, consistent with the overall style.

## 5. Design & Style
- **Aesthetic:** Cozy and nostalgic, inspired by a real notebook.  
- **Color Palette:** Black and white with soft shadows or subtle paper textures.  
- **Layout:** Clean, minimal, and responsive — fully functional on both desktop and mobile browsers.  
- **Mood:** Calm, focused, and slightly nostalgic.

## 6. Technical Requirements
- **Frontend:** React (or similar modern framework) with responsive layout.  
- **Backend:** Node.js or similar for user authentication and data storage.  
- **Database:** PostgreSQL, MongoDB, or Firebase for storing notes and folders.  
- **Hosting:** Cloud-based hosting with SSL.  
- **Data Sync:** Auto-save triggered on typing or blur events, synced to the user’s account on the server.

## 7. Success Metrics
- Users can create, edit, and organize notes without confusion.  
- Zero data loss during writing (due to reliable auto-save).  
- Positive feedback on simplicity and nostalgic design.

## 8. Future Considerations (Post-MVP)
- Note search or tagging system.  
- Collaborative or shared notes.  
- Theming (dark mode, custom colors).  
- Offline mode with sync-on-reconnect.
