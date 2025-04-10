This is for a new blank project folder. Do:
```
#Copy All sample code inside this repo. 
#You can do it manually or by git clone :)
git clone --branch master https://github.com/lfsegoro/tw4HowToInstall.git .
npm init -y
npm install tailwindcss @tailwindcss/cli
# this create tailwind.config.js
echo 'module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
' > tailwind.config.js
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

```
If You have already a running project (not empty folder).
Make sure in root of the project folder, Do:
```
# this create the input.css
echo '@tailwind base;
@tailwind components;
@tailwind utilities;

@import "tailwindcss";
' > input.css

# this create tailwind.config.js
echo 'module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
' > tailwind.config.js

npm install tailwindcss @tailwindcss/cli
npx @tailwindcss/cli -i input.css -o output.css --watch

```
Open tw4.html to see the result of the tailwind styling.
I am using Vscode, so dont forget to install extension Tailwind CSS Intellisense, if you need auto complete.
