# KKNotes - BSc Computer Science Resource Portal

KKNotes is a comprehensive web application designed for BSc Computer Science students. It serves as a centralized hub for accessing study materials, including lecture notes, question papers, and reference books, organized by year and semester.

The platform features a responsive student interface and a fully functional admin dashboard for content management.

## 🚀 Features

### Student Portal
*   **Year-wise Organization:** Dedicated sections for First Year (FY), Second Year (SY), and Third Year (TY).
*   **Semester Filtering:** Toggle between semesters (I-VI) to view relevant subjects.
*   **Resource Access:** Direct links to Notes, Question Papers, and Reference Books for each subject.
*   **Search Functionality:** Real-time search to quickly find subjects.
*   **Subject Information:** Detailed view of subject descriptions and examination patterns.
*   **Contact System:** Feedback form for students to reach out to administrators.

### Admin Dashboard
*   **Secure Access:** Login-protected admin area.
*   **Overview Stats:** Dashboard displaying total subjects, feedback count, and site visits.
*   **Subject Management:**
    *   Add new subjects.
    *   Edit existing subject details and resource URLs.
    *   Delete subjects.
*   **Feedback Management:** View, manage, and delete student feedback.
*   **Visit Tracker:** Real-time visit counter persisted via LocalStorage.

## 🛠️ Tech Stack

*   **Frontend Framework:** [React.js](https://reactjs.org/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **Routing:** [React Router v6](https://reactrouter.com/)
*   **Animations:** [Framer Motion](https://www.framer.com/motion/)
*   **Icons:** [Lucide React](https://lucide.dev/)
*   **Toast Notifications:** [Sonner](https://sonner.emilkowal.ski/)
*   **Data Persistence:** Browser LocalStorage (Simulating a backend database)

## 📦 Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd kknotes-bsccs
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm start
    ```
    The app will run at `http://localhost:3000`.

## 🔑 Admin Credentials

To access the Admin Dashboard (`/admin`), use the following default credentials:

*   **Username:** `admin`
*   **Password:** `admin123`

## 📂 Project Structure

```
src/
├── components/       # Reusable UI components (Navbar, Footer)
├── pages/           # Application pages
│   ├── Admin*.js    # Admin dashboard and management pages
│   ├── YearPage.js  # Dynamic page for FY/SY/TY
│   ├── Home.js      # Landing page
│   └── ...
├── data.js          # Initial mock data (Subjects, Feedback)
├── App.js           # Main component with Routing and Visit Tracker
└── index.js         # Entry point
```

---
&copy; 2025 KKNotes BSCCS. Built for students.