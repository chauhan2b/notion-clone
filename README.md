# Jotion — Notion-Style Notes App

A full-stack note-taking application inspired by Notion. Jotion allows authenticated users to create and organize nested documents, edit rich content, recover archived notes, and publish selected pages to the web.

**Live demo:** https://note-app-bice-three.vercel.app

## Features

- User authentication with Clerk
- Rich-text editing powered by BlockNote
- Nested document creation and organization
- Document search
- Page icons and cover images
- Image uploads using EdgeStore
- Archive, restore, and permanently delete documents
- Publish pages using shareable public links
- Responsive and resizable navigation
- Light and dark themes
- Real-time data storage with Convex

## Tech Stack

- **Framework:** Next.js 14, React 18, TypeScript
- **Styling:** Tailwind CSS, shadcn/ui, Radix UI
- **Backend and database:** Convex
- **Authentication:** Clerk
- **Editor:** BlockNote
- **File storage:** EdgeStore
- **State management:** Zustand
- **Deployment:** Vercel

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm
- Clerk and Convex accounts
- EdgeStore configuration for file uploads

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/chauhan2b/notion-clone.git
    cd notion-clone
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env.local` file:

    ```env
    NEXT_PUBLIC_CONVEX_URL=your_convex_deployment_url
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    ```

4. Configure Clerk as the authentication provider for Convex.

5. Start the development server:

    ```bash
    npm run dev
    ```

Open http://localhost:3000 in your browser.

## Available Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
