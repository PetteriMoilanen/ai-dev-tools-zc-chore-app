# Household Chore Manager - Project Scope

## Project Overview
A simple, robust, and self-contained fullstack web application to manage shared household chores, designed to be used on a shared screen or tablet (e.g., in a kitchen or living room).

## Technology Stack
- **Backend & Frontend Framework:** Django (Server-Side Rendering with Django Templates)
- **Database:** SQLite (built-in with Django, lightweight and perfect for local/household storage)
- **Styling:** Minimalist CSS Framework (Pico.css or Bulma) to ensure a clean, modern, and responsive user interface using semantic HTML with zero build tools.
- **User / Roommate Access:** Profile Selector (No Auth) — simple profile switching via a dropdown, making it seamless for housemates to view, update, and toggle their chores without managing passwords.

## Core Features & Scope
1. **Manual Assignment:** 
   - Ability to create chores with descriptions, difficulty levels, or frequencies.
   - Assign chores directly to specific roommate profiles.
2. **Due Dates & Deadlines:**
   - Set specific deadlines for chores.
   - Visual indicators (e.g., color-coding) for upcoming and overdue tasks.
3. **Chore Rotation:**
   - Automatic rotation logic (e.g., daily or weekly) to cycle chores among roommates fairly (e.g., trash duty, dishwashing).
4. **Interactive Dashboard:**
   - Single-page view of all tasks.
   - Quick "Complete" button to mark chores as done.
   - Profile switcher to filter chores for a specific roommate.

---

## Brainstorming Decisions & Q&A Summary

*   **Q: What kind of platform/interface would you like to build for this household chores manager?**
    *   *A: Web App (Frontend only or Fullstack)*
*   **Q: Do you want a simple frontend-only app, or a fullstack application with backend sync?**
    *   *A: Fullstack (API + DB + Web UI)*
*   **Q: Which chore-assignment and management features are essential for your MVP?**
    *   *A: Chore Rotation, Due Dates & Deadlines, Manual Assignment*
*   **Q: What technology stack do you prefer for the frontend, backend, and database?**
    *   *A: Django and SQLite*
*   **Q: For Django and SQLite, do you want to use classic Django Templates (SSR) or a separate React frontend?**
    *   *A: Django Templates (SSR)*
*   **Q: How would you like to style the application?**
    *   *A: Minimal Framework (Pico/Bulma)*
*   **Q: How should user/roommate identification be handled?**
    *   *A: Profile Selector (No Auth)*
