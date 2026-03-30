## Take‑home 1: Mid‑level Full‑Stack Engineer

**Task: Real‑estate Listing Search API + Frontend**

**Problem statement**  
You are building the core listing‑search backbone for a real‑estate broker's website.  
Given a mock "broker platform"‑style feed of properties, you must:

1. Design and implement:
   - A backend API (REST or GraphQL) that exposes:
     - `/listings` (search + filters: price range, beds, baths, property type, keyword).
     - `/listings/{id}` (property detail).
   - A simple frontend (e.g., Next.js or similar) that:
     - Displays a property search page with filters.
     - Shows a results list (no map) and a property detail page.

2. Use a relational DB (Postgres‑style) with:
   - Tables for `properties` and `agents`.
   - Indexes that support common search patterns (price, suburb, type, etc.).

3. Implement:
   - A basic role flag (e.g., `is_admin: boolean`) on the server.
   - Role‑aware behaviour: Admins can see extra metadata (e.g., internal status notes) that normal users cannot.

4. Add:
   - Pagination (offset‑ or cursor‑based).
   - URL‑friendly search (e.g., `/listings?suburb=Northside&price_min=500000`).

5. Deliver a clean, testable codebase:
   - At least 2–3 unit or integration tests (e.g., API endpoint tests or DB query tests).
   - A concise README with:
     - How to run the app.
     - How to seed the DB.
     - Example API calls.

**Evaluation focus**
- Clear separation of concerns (controller, service, DB).
- Sensible schema design and indexing.
- REST/GraphQL design and consistency.
- Ability to ship a small but complete module.
- Basic testing and documentation.
