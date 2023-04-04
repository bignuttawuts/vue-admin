npm init vue@latest

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

tailwind.config.js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

npm install @headlessui/vue @heroicons/vue