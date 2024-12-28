# LiveDocs - Real-time Collaborative Document Editor

A powerful Google Docs alternative built with modern web technologies that enables real-time collaboration at scale.

## ✨ Features

### Real-time Collaboration
- Live cursors showing collaborator positions
- Multiple users can edit simultaneously
- See who's currently active in the document

### Rich Text Editor
- Full markdown support
- Multiple formatting options
- Custom styling capabilities
- Floating comments and annotations

### Smart Comments
- Nested comment threads
- Tag other users
- Emoji reactions
- Real-time updates

### Powerful Sharing
- Invite editors and viewers
- Flexible access management
- Revoke access instantly
- Real-time notifications

### Enterprise-Ready
- Secure authentication with Clerk
- Performance monitoring with Sentry
- Fully responsive design
- Production-grade reliability

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js with App Router
- **Real-time Engine**: LiveBlocks
- **Styling**: Tailwind CSS + shadcn/ui
- **Authentication**: Clerk
- **Editor**: Lexical (by Meta)
- **Type Safety**: TypeScript
- **Monitoring**: Sentry

## 🚀 Getting Started

1. Clone the repository

2. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.