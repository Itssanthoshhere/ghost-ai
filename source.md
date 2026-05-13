# Ghost AI — Initial Project Setup

## Next.js App

```bash
npx create-next-app@latest ./
```

---

## shadcn/ui Setup

```bash
npx shadcn@latest init -d
```

Add components:

```bash
npx shadcn@latest add button card dialog input tabs textarea scroll-area
```

---

# UI Utilities

Install icons:

```bash
npm install lucide-react
```

Install utility libraries:

```bash
npm install clsx tailwind-merge
```

---

# Authentication — Clerk

## Install Clerk

```bash
npm install @clerk/nextjs
```

## Install Clerk Themes

```bash
npm install @clerk/themes
```

## Clerk Skills (Optional)

```bash
npx skills add clerk/skills
```

---

# Prisma Setup

## Install Prisma + PostgreSQL Dependencies

```bash
npm install prisma tsx @types/pg --save-dev
```

```bash
npm install @prisma/client @prisma/adapter-pg dotenv pg
```

---

## Initialize Prisma

```bash
npx prisma init --output ../app/generated/prisma
```

---

## Generate Prisma Client

```bash
npx prisma generate
```

---

## Prisma Skills (Optional)

```bash
npx skills add prisma/skills
```

---

# Liveblocks Setup

## Install Liveblocks Packages

```bash
npm install @liveblocks/client @liveblocks/react @liveblocks/react-ui @liveblocks/react-flow @xyflow/react
```

---

## Initialize Liveblocks

```bash
npx create-liveblocks-app@latest --init --framework react
```

---

## Install Liveblocks Server SDK

```bash
npm install @liveblocks/node
```

---

## Liveblocks Skills (Optional)

```bash
npx skills add liveblocks/skills
```

---

# Vercel Blob Storage

## Install Vercel Blob SDK

```bash
npm install @vercel/blob
```

---

## Environment Variable

Add to `.env.local`:

```env
BLOB_READ_WRITE_TOKEN=vercel_blob_rw_xxxxxxxxx
```

---

# Trigger.dev Setup

## Initialize Trigger.dev Project

```bash
npx trigger.dev@latest init -p proj_gmubdgvweoofrpdbyjng
```

---

## Install Trigger.dev Skills

```bash
npx skills add triggerdotdev/skills
```

---

## Initialize Trigger.dev in Project

```bash
npx trigger.dev@latest init
```

Choose:

- Trigger directory → `trigger`
- Example → `Simple (Hello World)`

---

## Start Trigger.dev Local Worker

```bash
npx trigger.dev@latest dev
```

Expected output:

```bash
○ Local worker ready [node]
```

---

# Additional AI Sidebar Dependencies

Install markdown rendering:

```bash
npm install react-markdown
```

Install Trigger.dev React hooks:

```bash
npm install @trigger.dev/react-hooks
```

Install AI SDK:

```bash
npm install @ai-sdk/google ai
```

---

# Current Ghost AI Stack

```txt
Next.js 16
TypeScript
Tailwind CSS
shadcn/ui
Clerk Authentication
Prisma ORM
PostgreSQL
Liveblocks Realtime Collaboration
React Flow Canvas
Vercel Blob Storage
Trigger.dev Background Jobs
React Markdown Rendering
Google AI SDK
```
