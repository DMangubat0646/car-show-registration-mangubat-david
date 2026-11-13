# Car Show Registration System

Registration system for **Car Show 2027** (AutoVista Events, Sorsogon City Coliseum). Participants register as Exhibitors, Competitors or VIPs, and event staff track registrations and payments from a dashboard.

Course project for Integrative Programming 2 (API Backend Development), CCDI Sorsogon Campus. Deadline: November 25, 2026.

## Team

| MEMBER | ROLE |
| ------ | ---- |
| Diomar Mangubat | Frontend Developer |
| Andrea Lucas David | Backend Developer |

## Tech Stack

| PART | TECHNOLOGY |
| ---- | ---------- |
| Backend API | C# / .NET 10, EF Core, SQLite, FluentValidation, Scalar |
| Frontend | React JS (Vite), Tailwind CSS / Bootstrap |

## Repository Layout

```
car-show-registration-mangubat-david/
├── backend/       C# Vertical Slice solution (from the course template)
├── frontend/      React app (Vite)
├── docs/
│   └── screenshots/   Scalar test screenshots and other evidence
└── README.md      team, roles, how to run both apps
```

## How to Run

### Backend

Requires the .NET 10 SDK.

```bash
cd backend
dotnet run --project Api
```

The API runs at `http://localhost:5205`, and the Scalar API docs are at `http://localhost:5205/scalar/v1`.

### Frontend

The React app has not been added yet. Once it is in `frontend/`:

```bash
cd frontend
npm install
npm run dev
```

The dev server runs at `http://localhost:5173`, which is the origin the API's CORS policy allows.

## API Contract

The frontend and backend share one JSON contract for registrations. Do not change it without telling your partner. The shapes are defined in the project requirements document.
