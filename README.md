# VTR-Template
## A Template of Vite + React + Tailwind JIT Project

Read Here
https://tailwindcss.com/docs/guides/create-react-app

### Create A public folder in root directory
that way you can store images there and you won't have to write import statements everytime you use an image

##### 1. Create A Vite/Create-React-App
```console
npm init vite@latest
```

##### 2. Install tailwindcss postcss and autoprefixer
```console
npm install tailwindcss postcss autoprefixer -D
```

##### 3. Install Postcss and Tailwindcss Config files
```console
npx tailwindcss init -p
```

##### 4. Add below commands into modules.exports object of tailwind.config.js
```js
  content: ['./src/**/*.{js,jsx,ts,tsx}', './index.html'],
```

##### 5. Create an index.css file in src folder (if it doesn't exist)

##### 6. index.css file should initially contain below commands only
```js
@tailwind base;
@tailwind components;
@tailwind utilities;
```

##### 7. Import index.css file into main.jsx
now you can use tailwind everywhere in your react components
