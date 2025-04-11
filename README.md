This is for a new blank project folder. Do:
```
#Copy All sample code inside this repo. 
#You can do it manually or by git clone :)
git clone --branch master https://github.com/lfsegoro/tw4HowToInstall.git .
npm init -y
npm install tailwindcss @tailwindcss/cli
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css

```
If You have already a running project (not empty folder).
Make sure in root of the project folder, Do:
- copy ./src/input.css to your src folder
- copy tailwind.config.js to your root folder
```
npm install tailwindcss @tailwindcss/cli
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css

```
Open tw4.html to see the result of the tailwind styling.
I am using Vscode, so dont forget to install extension Tailwind CSS Intellisense, if you need auto complete.

Tips: 

If no autocomplete not show when you type class="",

try to "ctrl + space"
