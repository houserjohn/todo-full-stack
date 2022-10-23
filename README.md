# Todo Full Stack README

This is a mono-repo for my todo full stack application that I am building to test out some new technologies

Here are the technologies this project uses:

Frontend:
* React
* Recoil
* Typescript
* Tailwind CSS
* Apollo Client

Backend:
* Go
* AWS

Misc:
* Kubernetes
* Docker
* GraphQL

## Developer Notes

* Initializing this project with React, Typescript, and Tailwind
```
npx create-react-app todo-app --template typescript
cd todo-app
npm install -D tailwindcss postcss autoprefixer 
npx tailwindcss init -p
```
Put the following text in the file name "tailwind.config.js"
```
content: [
    './src/**/*.{js,jsx,ts,tsx}',
],
```
Finally, add the following to "src/index.css"
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```