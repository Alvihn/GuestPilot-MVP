![GuestPilot Screenshot](https://github.com/user-attachments/assets/8acd2f5d-1ace-40a9-8128-88022da6c107)

````
# GuestPilot MVP

Podcast guest management automation built with **Next.js**, **Express**, and **Prisma**. Manage guests, automate emails, and sync with Google Calendar—production-ready and responsive.

## Features

- **Auth0 Authentication** – Secure user login and profile management  
- **Guest Management** – CRUD operations with status tracking and search  
- **Calendar Integration** – Google Calendar sync & event creation  
- **Email Automation** – Invitations, reminders, and thank-you emails  
- **Pipeline Tracking** – Drag-and-drop guest workflow  
- **Modern UI** – Responsive React components with real-time updates  

## Quick Start

1. **Clone repo**  
```bash
git clone <repo-url>
cd guestpilot-mvp
````

2. **Setup environment variables**

```bash
cp backend/.env.example backend/.env
cp .env.example .env.local
```

3. **Install dependencies**

```bash
# Backend
cd backend
npm install
# Frontend
cd ..
npm install
```

4. **Setup database**

```bash
cd backend
npx prisma migrate dev
npx prisma generate
```

5. **Run app**

```bash
# Backend
cd backend
npm run dev
# Frontend
cd ..
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000)

### Docker

```bash
docker-compose up --build
```

## License

MIT

```
