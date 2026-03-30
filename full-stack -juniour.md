## Take‑home 2: Junior Full‑Stack Engineer

**Task: Auth + Simple Buyer Portal (Favourites)**

**Problem statement**  
You are building part of the buyer portal for a real‑estate broker.  
Given a simple skeleton for an API, you must:

1. Implement:
   - User registration and login (email + password).
   - JWT or session‑style auth (in‑memory or simple DB‑backed).

2. Create a simple buyer dashboard page that:
   - Shows the user's name and role.
   - Lists "My Favourites" (properties) stored against the user.
   - Allows the user to:
     - Add/remove a property to/from favourites.
   - Enforces that users can only see and modify their own favourites.

3. Add basic frontend:
   - A login page and a dashboard page.
   - A simple form or button flow to "like" a property.

4. Implement:
   - Basic server‑side validation and error handling.
   - A tiny DB layer (e.g., `users`, `favourites` tables or equivalent).

5. Add:
   - A short README with:
     - How to run the app.
     - Example flows (e.g., sign up → login → add favourite).

**Evaluation focus**
- Understanding of auth flows and basic security (no raw passwords in DB).
- Simple DB design and CRUD operations.
- Clear separation between frontend and backend.
- Ability to read and extend existing code.
- Basic UX thinking (e.g., clear success/error messages).
