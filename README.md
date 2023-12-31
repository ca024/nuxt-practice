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

### Add Unique Routing
To create a dynamic and unique path, create a folder/file inside the pages folder and name the folder/file to the unique path enclosing dynamic parts in square bracket (e.g. [name]-[id])

### Navigate using elements
To navigate to a path using an element, use NuxtLink component and define the path on the attribute "to"
If the path is dynamic, use navigateTo method instead of a NuxtLink component

### Router-based nested components
To render some components based on router, simply use NuxtPage component within the folder/file, the succeeding folder/file will render the component based on router match

### Change page title
Use useHead component and define title attribute

### Adding pinia
```bash
npm @pinia/nuxt
```
Add '@pinia/nuxt' to the modules in nuxt.config.ts
Create stores folder
Add <my-store>.ts to define stores

### Adding vuetify
```bash
npm i -D vuetify vite-plugin-vuetify
npm i @mdi/font
```
Configure nuxt.config.ts refer to [this](https://vuetifyjs.com/en/getting-started/installation/#using-nuxt-3)