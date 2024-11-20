# shadcn-starter 📌
shadcn-v0 starter by **HengkerKucing** ⭐⭐⭐
* link https://v0.dev/shadcn

## windows
<ins> open your cmd </ins>
``` 
cd <folder_name>
```
```
code .
```

# Get Started 🚀

1. initialization project
```
npx create-next-app@latest <project_name> --typescript
```
2. install tailwindcss postcss autoprefixer
```
npm install tailwindcss postcss autoprefixer
```
3. make config file tailwindcss
```
npx tailwindcss init
```
4. install lucide-react
```
npm install lucide-react
```
5. initialization shadcn-ui
```
npx shadcn@latest init
```
6. add ui component from shadcn
```
npx shadcn@latest add <component_name>
```
7. replace content on `tailwind.config.js`
   ```
    content: [
        './pages/**/*.{ts,tsx}',
        './components/**/*.{ts,tsx}',
        './app/**/*.{ts,tsx}',
        './src/**/*.{ts,tsx}',
        ],
   ```
8. add `/** @type {import('tailwindcss').Config} */` on top of `tailwind.config.js`

  + **example for step 7 & 8**
   ```
   /** @type {import('tailwindcss').Config} */
    module.exports = {
    	darkMode: ["class"],
    	content: [
    	  './pages/**/*.{ts,tsx}',
    	  './components/**/*.{ts,tsx}',
    	  './app/**/*.{ts,tsx}',
    	  './src/**/*.{ts,tsx}',
    	],
      <continue of code>
   
  ```

### End of Tutorial
⭐ **support please by give the repo stars** ⭐
