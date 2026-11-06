
# LinkStore

**A full-stack bookmarking application built with Next.js 16, React 19 and MongoDB, featuring user authentication, tag-based organisation and searchable resources.**

LinkStore is a personal library for saving and organising useful URLs. Rather than relying on conventional bookmark folders, users can create their own tags and search for resources when they need them.

The project was built to explore full-stack application development using Next.js, including authentication, database persistence, user-specific content and interactive frontend components.

**[Try the Live App](https://linkstore-app.onrender.com/)** | **[Source Code](https://github.com/DB-1984/Linkstore-URL-Resource-Library)**

*The live application is hosted on Render and may take a minute to become available after a period of inactivity.*

---

## Video Demonstration

[![Watch the LinkStore demonstration](https://img.youtube.com/vi/Z-iFv1SJNik/hqdefault.jpg)](https://www.youtube.com/watch?v=Z-iFv1SJNik)

*Click the image to watch LinkStore in action on YouTube.*

---

## Technology Stack

- **Next.js 16** — Full-stack React framework and application routing
- **React 19** — Component-based user interface
- **JavaScript** — Application logic
- **MongoDB** — Document database
- **Mongoose** — Data modelling and database operations
- **NextAuth v5** — Authentication and session management
- **Google OAuth** — Third-party account authentication
- **bcryptjs** — Password hashing and verification
- **Tailwind CSS v4** — Responsive styling
- **Radix UI / shadcn/ui** — Accessible interface components
- **Lucide, Sonner and Vaul** — Icons, notifications and drawer interfaces
- **MDX** — Rich content support
- **Resend** — Transactional email integration

---

## Key Features

### Personal Link Library

Users can save useful URLs and organise them into a personal collection.

- Persistent storage using MongoDB
- Custom tags for flexible categorisation
- Text search for finding saved resources
- Interactive management interface

The tag-based structure offers an alternative to traditional bookmark folders, allowing users to organise resources by topic rather than a fixed hierarchy.

### User Authentication

LinkStore supports account authentication through NextAuth, using both Google OAuth and email/password credentials.

- Google account sign-in
- Credentials-based authentication
- Password hashing and verification using bcryptjs
- MongoDB adapter for authentication data
- JWT-based sessions

The authentication implementation combines the MongoDB adapter with Mongoose models for application data.

### Interactive User Interface

The interface uses Tailwind CSS and components built around Radix UI primitives.

- Dialogs for contextual interactions
- Dropdown menus and tooltips
- Responsive drawer components
- Toast notifications for user feedback
- Reusable, component-based UI elements

### Additional Integrations

The project also incorporates:

- **MDX** for richer formatted content
- **Resend** for transactional email functionality

---

## Technical Approach

### Full-Stack Next.js

LinkStore uses Next.js for both its React frontend and server-side functionality.

This provides an opportunity to work with application routing, server-side operations, database connectivity and authentication within a single framework.

### Database Modelling

MongoDB provides persistent storage, while Mongoose defines the application's data models.

The project explores how user-generated resources can be organised and retrieved using a flexible, tag-based structure.

### Authentication Architecture

NextAuth manages authentication using two providers:

- Google OAuth
- Email/password credentials

The MongoDB adapter handles authentication-related persistence, while Mongoose is used for application-specific database operations.

JWT sessions support the credentials authentication flow.

### Component-Based UI

The interface combines React components with Radix UI primitives and Tailwind CSS.

This separates presentation and interaction logic into reusable components, while providing consistent handling of dialogs, menus, notifications and responsive layouts.

---

## Local Development

### Requirements

- Node.js and npm
- A MongoDB database
- Authentication provider credentials
- Environment variables for authentication and other configured services

### Installation

Clone the repository:

```bash
git clone https://github.com/DB-1984/Linkstore-URL-Resource-Library.git
```

Navigate into the project directory:

```bash
cd Linkstore-URL-Resource-Library
```

Install dependencies:

```bash
npm install
```

Configure the required environment variables for your database, authentication providers and any additional services.

Start the development server:

```bash
npm run dev
```

Open http://localhost:3000 in your browser.

For a production build:

```bash
npm run build
npm run start
```

---

## Project Context

LinkStore is a self-directed portfolio project developed to extend my experience beyond commercial WordPress and PHP development into modern full-stack JavaScript applications.

It provides practical experience with Next.js, React, database modelling, authentication, third-party integrations and persistent user data.

The project also reflects a broader interest in building software around everyday problems, with an emphasis on usability and straightforward workflows.

---

## Links

- **Live Application:** https://linkstore-app.onrender.com/
- **Video Demonstration:** https://www.youtube.com/watch?v=Z-iFv1SJNik
- **Developer Portfolio:** https://david-brandon.onrender.com/
- **GitHub Profile:** https://github.com/DB-1984
