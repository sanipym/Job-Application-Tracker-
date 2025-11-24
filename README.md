# Job Application Tracker 
Ruby on Rails Job Application Tracker

## Core Features:
```

Track job applications (company, position, status, dates)
Application status workflow (Applied → Interview → Offer → Accepted/Rejected)
Document management (resumes, cover letters)
Interview scheduling and notes
Analytics dashboard
```

## Architecture Diagram
```
┌─────────────────────────────────────────────┐
│              Presentation Layer              │
│  (Controllers, Views, Decorators, Helpers)   │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│           Application Layer                  │
│  (Service Objects, Form Objects, Commands)   │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│              Domain Layer                    │
│    (Models, Value Objects, Repositories)     │
└──────────────────┬──────────────────────────┘
                   │
┌──────────────────▼──────────────────────────┐
│          Infrastructure Layer                │
│  (Database, Cache, External APIs, Jobs)      │
└─────────────────────────────────────────────┘