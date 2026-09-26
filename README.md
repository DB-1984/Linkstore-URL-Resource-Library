# LinkStore

**[Try the live app](https://linkstore-app.onrender.com/)** (the Render service may take a minute to wake up).

LinkStore is a personal library for useful links. Users can save URLs, organise them with custom tags and use text search to find them again. It offers a more flexible way to keep track of resources than a growing collection of bookmark folders.

I built it with **Next.js 16 and React 19**, using MongoDB and Mongoose to store data. Authentication uses NextAuth with the MongoDB adapter, and bcryptjs handles password hashing.

## Interface

The interface uses Tailwind CSS v4 and components built from Radix UI primitives. Dialogs, menus, tooltips and drawers support the main interactions, while Lucide icons and Sonner notifications provide visual feedback. The project is written in **JavaScript**.

## Additional features

MDX support allows for richer formatted content alongside the link library, and Resend is integrated for transactional email.

## Built with

* Next.js 16 and React 19
* JavaScript
* MongoDB and Mongoose
* NextAuth and bcryptjs
* Tailwind CSS v4
* Radix UI and shadcn/ui components
* Lucide icons, Sonner and Vaul
* MDX and Resend
