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

## UI Utilities

```bash
npm install lucide-react
```

```bash
npm install clsx tailwind-merge
```

---

# Authentication — Clerk

Install Clerk:

```bash
npm install @clerk/nextjs
```

Install Clerk themes:

```bash
npm install @clerk/themes
```

(Optional) Add Clerk skills:

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

