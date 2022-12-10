# Tailwind-for-production



**Step 1: ** Initialises directory as a Node project\
```
npm init -y
```
**Step 2: ** install required packages\
```
npm install -D tailwindcss postcss autoprefixer vite
```
**Step 3: **
```
npx tailwindcss init -p
```
**Step 4: ** Create a css file "input.css". Add the following code in it\
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
**Step 5: ** Make a new file "index.html" add the index.css in it using ***link***
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./input.css" />
    <title>Tailwind css</title>
  </head>
  <body>
  </body>
</html>

```
**Step 6: ** In your "tailwind.config.js" file replace "config[]" with "config["*"]"

**Step 7: ** Add "start":"vite" to your scripts in package.json

**Step 8: ** To run the dev server
```
npm run start
```
