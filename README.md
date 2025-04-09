Make sure in root of the project folder, run :
```
npm init -y
npm install tailwindcss @tailwindcss/cli

```
Next (Optional) dont need if you have your own files:
```
#Copy All sample code inside this repo. You can do it manyally or by git clone :)
git clone --branch master https://github.com/lfsegoro/tw4HowToInstall.git .
```
Next:
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
