# Workforce-Tracking-System
The purpose of this system is to build a centralized, secure, scalable, and role-based Intern Management &amp; Workforce Tracking Platform that can later be integrated into the Uptoskills ecosystem and portal.

## Suggested Folder structure

frontend/
├── app/
├── features/
│   ├── auth/
│   ├── attendance/
│   ├── ratings/
│   ├── notifications/
│   └── dashboard/
│
├── shared/
│   ├── components/
│   ├── hooks/
│   ├── utils/
│   ├── api/
│   └── types/
│
├── store/
└── layouts/

backend/
├── modules/
│
│   ├── auth/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── validators/
│   │   ├── routes/
│   │   └── types/
│
│   ├── users/
│   ├── attendance/
│   ├── ratings/
│   ├── notifications/
│   ├── uploads/
│   └── audit/
│
├── shared/
│   ├── middleware/
│   ├── utils/
│   ├── constants/
│   └── errors/
│
├── infrastructure/
│   ├── db/
│   ├── logger/
│   └── storage/
│
├── config/
└── app.ts
