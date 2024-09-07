# Prisma

## Basic Prisma Commands

**Install Prisma CLI**
```bash
npm install @prisma/cli --save-dev
```

**Initialize Prisma in a project**
```bash
npx prisma init
```

**Generate Prisma Client**
```bash
npx prisma generate
```

**Deploy Prisma schema to the database**
```bash
npx prisma db push
```

**Run database migrations**
```bash
npx prisma migrate dev --name <migration_name>
```

**Reset the database and apply migrations**
```bash
npx prisma migrate reset
```

**Check for migration status**
```bash
npx prisma migrate status
```

**Create a new migration**
```bash
npx prisma migrate dev --name <migration_name>
```

**Apply pending migrations**
```bash
npx prisma migrate deploy
```

## Prisma Database Commands

**Pull the database schema into Prisma**
```bash
npx prisma db pull
```

**Seed the database**
```bash
npx prisma db seed
```

**View Prisma Studio (GUI for database)**
```bash
npx prisma studio
```

## Prisma Project Management

**Validate the Prisma schema**
```bash
npx prisma validate
```

**Format the Prisma schema**
```bash
npx prisma format
```

## Miscellaneous

**Check Prisma version**
```bash
npx prisma --version
```
