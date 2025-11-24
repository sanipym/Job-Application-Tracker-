# Job Application Tracker 
Ruby on Rails Job Application Tracker

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