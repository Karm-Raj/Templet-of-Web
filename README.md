# Templet-of-Web
Templet of website using HTML, CSS, JavaScrip &amp; TailwindCSS

# setup TailwindCSS
 documentation Link https://tailwindcss.com/docs/installation/using-vite
# using cdn
    1. In html file go to head tag and paste 
```
<script src="https://unpkg.com/@tailwindcss/browser@4"><script>
```
2. you can customize tailwindCSS by pasting in head tag 
```
<style type="text/tailwindcss">@theme {--color-clifford: #da373d;}</style>
```
    3. just use normally :)

 # using CLI
Step 1. Need Node.js automatic install npm to check npm version using powershell 
```
npm --version
```
Step 2. now go to your project main direcotry open terminal 
```
npm install tailwindcss @tailwindcss/cli
```
Step 3. make a new folder called src inside CSS file any name like input.css and paste inside 
```
@import "tailwindcss";]
```
Step 4. run this automatic genarate output file 
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
Step 5. add css file to head tag 
```
<link href="./output.css" rel="stylesheet">
```

Step 6. open package.json Add Scripts class like this 
```
{
  "scripts": {
    "build":"npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch"
  },
  "dependencies": {
    "@tailwindcss/cli": "^4.0.5",
    "tailwindcss": "^4.0.5"
  }
}
```
step 7. Next time you open VS code just run terminal and
```
npm run build
```

# Deployment
1. just link output.css form src folder file in html, if not link in case
    in this case Style_out.css is output file of tailwind css 
2. now copy output file and paste in final web folder
3. final web folder is ready for deploy.