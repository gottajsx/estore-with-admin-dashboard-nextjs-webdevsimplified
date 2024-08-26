## Getting Started

First, run the development server:

```
npx create-next-app@latest estore-with-admin-webdevsimplified

TypeScript ? Yes
EsLint ? Yes
Tailwind CSS ? Yes
src/ directory ? Yes
App Router ? Yes
import Alias ? No
```

To start the app:
```
npm run dev
```

## Usage of Prisma
```
npm install typescript ts-node @types/node --save-dev
```
As `typescriot` and `@types/nide` should be already installed, we only need, we only need:
```
npm install --save-dev ts-node
```
Then install Prisma cli:
```
npm install prisma --save-dev
```
Finally, set up the Prisma ORM:
```
npx prisma init --datasource-provider sqlite
```
Prisma ORM creates a default `.env` file at your projects root containing value for
```
DATABASE_URL=
```
## Prisma schemas

We can define database schemas from inside `schema.prisma` file.

## Database creation

To create the database:
```
npx prisma migrate dev --name init
```