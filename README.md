# Nuxt Practice

### Create a Nuxt app

```bash
npx nuxt init <app-name>
```

### Install all dependencies
```bash
npm install
```

### Start development server
```bash
npm run dev
```

### Add Tailwind CSS
```bash
npm install @nuxtjs/tailwindcss
```
Add '@nuxtjs/tailwindcss' to the modules in nuxt.config.ts

### Design and Code the UI

### Add Page-Based Routing
Create pages folder in the root directory  
Create index.vue to route '/'' path to index.vue  
Add NuxtPage component to app.vue - detects the current path and render the appropriate vue page  

### Auto-import vue components
Create components folder in the root directory  
Create vue components within that folder  
Use the component in another component, no need to import  
When the components is inside a nested folder of components folder, to use the component, folder name is appended to the component name  

### Add Dynamic and Optional Routing
To create a static routing path, create a folder/file inside the pages folder and name the folder/file to the static path  
To create a dynamic routing path, create a folder/file inside the pages folder and name the folder/file to the dynamic path enclosing it with square brackets  
To create a dynamic and optional routing path, create a folder/file inside the pages folder and name the folder/file to the dynamic path enclosing it with double square brackets  