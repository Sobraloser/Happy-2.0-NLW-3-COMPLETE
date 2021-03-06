# Happy 2.0
This project was developed during the Next Level Week 3.

![ProjectImage](https://github.com/Sobraloser/Happy-2.0-NLW-3-COMPLETE/blob/main/Happy-Git_Image.png?raw=true)

# About the project

Happy is a Web and Mobile application that allows users to register and find orphanages. Visiting users are offered details of the orphanage, such as times and instructions for visiting the orphanage.

This project was conceived thinking about the 12th of October, where Children's Day is celebrated, created in order to help users find orphanages and bring joy to children.

This application was developed during the Next Level Week # 3, a Rocketseat project.

# Techs

* Express
* Axios
* Leaflet
* Typescript
* TypeORM
* SQLite
* Json Web Token (JWT)
* Yarn
* NodeJs
* ReactJS
* React Native

# Features

- Login page, made for administrators to approve registration requests.
- Users can create and request new orphanages to be approved by admins
- Admin can approve, reject, or update orphanages
- Image upload in create new orphanage
- Used leaflet map to show the registered orphanages
- Send email to change password

# How to install

## Prerequisites

1. NodeJS installed
2. Yarn or NPM installed
3. Expo installed, for mobile
4. Git, to clone this repository


## Step 1

### Cloning the repository

```bash
git clone https://github.com/Sobraloser/Happy-2.0-NLW-3-COMPLETE.git
```

## Step 2

### Installing dependencies

```yarn
yarn
```

or

```npm
npm install
```

## Step 3

### Creating migration

```bash
yarn migration:run
```

or 

```bash
npm run migration:run
```

## Step 4

### Initializing the application

```bash
yarn dev
```

or

```bash
npm run dev
```

# Production site

<a href="https://happy-project-web.vercel.app">Happy uploaded on Vercel<a>
