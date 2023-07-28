# Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL, 2023


## Getting Started

Start by creating a new Next.js project using create-next-app:
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.



```bash
npx create-next-app@latest my-app --typescript --tailwind --eslint

```
Run the shadcn-ui init command to setup your project:
- [shadcn-ui](https://ui.shadcn.com/docs/installation/next) - learn about shadcn-ui features.


```bash
npx shadcn-ui@latest init

```

Run development server by following commands:


```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Install @clerk/nextjs
Once you have a Next.js application ready, you need to install Clerk's Next.js SDK
- [Clerk's Next.js SDK](https://clerk.com/docs/nextjs/get-started-with-nextjs) - learn about Clerk's Next.js SDK.

```bash
npm install @clerk/nextjs
```
 
## Install Zustand
- [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) - for state management.

```bash
npm install zustand
```

## React Hook Form
Building forms with React Hook Form and Zod.
zod library is used to validate the React hook form.
```bash
npx shadcn-ui@latest add form
npx shadcn-ui@latest add input
```


## Install prisma ORM for database management
```bash
npm install -D prisma
```
```bash
npm install @prisma/client
```
```bash
npx prisma init
```


## planetscale - mysql

- [planetscale - mysql](https://planetscale.com/) - learn about planetScale-mySql documentation.
 After updating .env file and schema prisma and adding model store run the following command:
 ```bash
npx prisma generate 
```

then run this command to push schema into database
```bash
npx prisma db push 
```

## Install react-hot-toaste 
React Hot Toast is a library that aims to include toast notifications in your React applications easily and intuitively.

```bash
npm react-hot-toaste
```
## Install axios to make HTTP requests 
```bash
npm install axios
```


## To reset the database run the follwing command:

1.
```bash
npx prisma migrate reset
```
2. 

```bash
npx prisma genetare
```
3. 

```bash
npx prisma db push 
```

## Next-Cloudinary:
High-performance image delivery and uploading at scale in Next.js powered by Cloudinary

```bash
npm install next-cloudinary
```


