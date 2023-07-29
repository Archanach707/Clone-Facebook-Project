# Clone-Facebook-Project

Please check this link for setup: https://github.com/Archanach707/Clone-Facebook-Project/assets/54771334/17b0a9bc-d6a2-4e67-9a9e-72ef142d9c95)

To setup tailwind css, run these commands
1. npm init -v // This initializes the directives as a NodeJs project
2. npm install -D tailwindcss postcss autoprefixer vite // install requrired packeges.
3. npx tailwindcss init -p
4. Create a css file "input.css", add it to your html and edit it with this content:
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
5. In your tailwind.confing.js file replace content:[], with content:[*],
6. Add "start":"vite" to your script in package.json
7. ** For Run** npm run start command to start a dev server




