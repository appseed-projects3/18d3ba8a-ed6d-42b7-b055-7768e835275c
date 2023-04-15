# React Argon Design `full-stack`

Full-Stack Seed project generated by **[React App Generator](https://appseed.us/generator/react/)** top of *Argon Design* design. The backend logic is provided by a simple, `easy-to-extend` API Server that manages the Authentication flow (login, registration, logout) using `JSON Web Tokens` (JWT).

- 👉 [React Argon Design](https://react-argon-design.appseed-srv1.com/login-page) - LIVE Demo (from a similar product)

- 🚀 Built with [React App Generator](https://appseed.us/generator/react/), timestamp `2023-04-15 11:37`

<br />

![React Argon Design - Open-Source Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/206225228-85e663a2-40e6-4346-bff2-c5c3ebd7dc4b.png)



<br >

## ✨ `React` Argon Design System

- Design crafted by *[Creative-Tim](https://bit.ly/3fKQZaL)*
- Innovative **Material Kit Design**
- Full-stack ready
- `UI Kit`: 750+ components, `4 Sample Pages`  

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- |  
| `v14.0.0` | ✅ | ❌ |
| `v15.0.0` | ✅ | ❌ | 
| `v16.15.0` | ✅ | ✅ | 


<br />

## ✨ `NodeJS API` Features

- Stack: `NodeJS` / `Express` / **SQLite** 
- `TypeScript`, Joy for validation
- **DB Layer**: `TypeORM`, `SQLite` persistence
- **Auth**: Passport / `passport-jwt` strategy
- [API Definition](https://docs.appseed.us/boilerplate-code/api-unified-definition) - the unified API structure implemented by this server

<br />

> `Tests` (compatibility matrix)

| NodeJS | NPM | YARN | 
| --- | --- | --- | 
| `v18.0.0`  | ❌ | ✅ |
| `v17.0.0`  | ❌ | ✅ |
| `v16.13.0` | ❌ | ✅ | 
| `v16.0.0`  | ❌ | ❌ | 


<br /> 

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-nodejs`

```bash
$ cd api-server-nodejs
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Run the SQLite migration via TypeORM

```bash
$ npm run typeorm migration:run
// OR 
$ yarn typeorm migration:run
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ npm run dev
// OR
$ yarn dev
```

The API server will start using the `PORT` specified in `.env` file (default 5000).

<br /> 

## 👉 Codebase Structure

```bash
< ROOT / src >
     | 
     |-- config/                              
     |    |-- config.ts             # Configuration       
     |    |-- passport.ts           # Define Passport Strategy             
     | 
     |-- migration/
     |    |-- some_migration.ts     # database migrations
     |
     |-- models/                              
     |    |-- activeSession.ts      # Sessions Model (Typeorm)              
     |    |-- user.ts               # User Model (Typeorm) 
     | 
     |-- routes/                              
     |    |-- users.ts              # Define Users API Routes
     | 
     | 
     |-- index.js                   # API Entry Point
     |-- .env                       # Specify the ENV variables
     |                        
     |-- ************************************************************************
```

<br />

## 👉 SQLite Path

The SQLite Path is set in `.env`, as `SQLITE_PATH`

<br />

## 👉 Database migration

> Generate migration:

```bash
$ yarn typeorm migration:generate -n your_migration_name
```

> run migration: 

```bash
$ yarn typeorm migration:run
```

<br />

<br />

## [React Argon Design PRO](https://appseed.us/product/argon-design-system-pro/full-stack/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

`Argon Design React PRO` is built with over 100 frontend individual elements, like buttons, inputs, navbars, alerts or cards, giving you the freedom of choosing and combining. The product comes with a simple JWT authentication flow: login/register/logout. 

- 👉 [React Argon Design PRO](https://appseed.us/product/argon-design-system-pro/full-stack/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![React Argon Design PRO - Premium Fullstack starter crafted by Creative-Tim and AppSeed.](https://user-images.githubusercontent.com/51070104/206378423-541acda7-1022-419e-998e-716ade757906.png)

<br />

---
**React Argon Design** - Full-Stack Seed project generated by **[App Generator](https://appseed.us/generator/)**.
