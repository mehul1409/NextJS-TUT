# NextJS

Full-Stack React Framework means both frontend and backend can be done only by NextJS.

## Features:-

- server side rendering
- simple routing
- static site generation
- optimized performance
- Hot code reloading
- API routes

## Advantages over React.js

1. Search Engine Optimization
2. Production Ready
3. Image Optimization
4. Data Fetching Methods
5. NextJS server is **700x faster**
6. Typescript Support

## Folder Structure

- App Directory
- Layouts
- Server Component : we can't use React hooks in server side component
- Fetch API Extended

### Create Next app:-

```bash
npx create-next-app@latest appName
```

### pages:-

page.jsx is the main page

layout.jsx shared components with its children

head.js contain meta data for the page

loader.jsx create loading UI

not-found.js custom not found pages

## Routing:-

![Shows How routes works!](/public/ReadmeImages/route.jpeg)

- Here app is the / route,
- /dashboard -> Dashboard Route
- /dashboard/setting -> Setting Route
- /dashboard/setting/profile -> Profile Route

1. **[] this make a dynamic route**

2. **() this folder contains similar type of pages and we dont want to add folder name in route**

app->(auth)-|login
            |signup

/login is the login route instead of /auth/login

## Server and Client Component:-

### Server Component

![What is Server Component?](/public/ReadmeImages/server.png)

### Client Component

![What is Client Component?](/public/ReadmeImages/client.png)

### When to use Client and Server Component

![When to use Client and Server Component?](/public/ReadmeImages/usesOfserverandClient.png)

**We can't directly use server side component in client side. For this we want to pass server side component as children in client side component and then we can use this.** 
 

