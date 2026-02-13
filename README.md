# IB Recruiting CRM

A specialized Customer Relationship Management (CRM) tool designed for Investment Banking recruiting. This application helps you track target firms, manage networking contacts, log interactions, and stay on top of application deadlines and follow-ups.

## Features

*   **Target Firms Tracker:** Manage a list of target firms with details like office location, division, ranking, and application status.
*   **Contact Management:** Keep track of bankers and recruiters, including connection types (alumni, cold outreach, etc.) and interaction history.
*   **Interaction Logging:** Log emails, calls, and coffee chats. The system automatically schedules a follow-up reminder for 48 hours later.
*   **Follow-up Calendar:** A dedicated view for upcoming tasks, interviews, and assessments.
*   **Analytics Dashboard:** Visualize your progress with charts showing application status, contact outreach stats, and top-ranked firms.
*   **Calendar Integration:** Export reminders to Google Calendar or download `.ics` files for Outlook/Apple Calendar.
*   **Data Persistence:** Powered by Supabase for secure cloud storage.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/simongt18/ib-recruiting-crm.git
    ```
2.  **Open the Application:**
    Simply open `index.html` in any modern web browser (Chrome, Edge, Safari).

## Configuration

This project uses Supabase for the backend.

To set up the database schema, the following tables are required:
*   `firms`
*   `contacts`
*   `interactions`
*   `reminders`

*Note: Row Level Security (RLS) is enabled to ensure users can only see their own data.*

## Tech Stack

*   **Frontend:** HTML5, Tailwind CSS, React (via CDN), Babel (via CDN).
*   **Backend:** Supabase (PostgreSQL, Auth).
*   **Icons:** FontAwesome.
*   **Fonts:** Inter & Playfair Display.

## License

MIT