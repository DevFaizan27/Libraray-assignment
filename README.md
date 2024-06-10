# Libraray-assignment
1. initialize the project using-
     npm create vite@latest .//in same folder
     npm install

2. setup tailwind css
     npm install -D tailwindcss
     npx tailwindcss init

3.  Update your tailwind.config.js file:
      module.exports = {
      purge: ['./index.html', './src/**/*.{js,jsx,ts,tsx}'],
      darkMode: false, // or 'media' or 'class'
      theme: {
        extend: {},
        },
       variants: {
      extend: {},
  },
      plugins: [],
};

4.Create a src/index.css file and add the following:
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

5. develop app
6. npm run dev
