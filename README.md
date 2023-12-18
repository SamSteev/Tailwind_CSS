## Directly Opening Tailwindcss
          Step 1 : Download the zip file from the github and extract into one folder.
          
          Step 2 : Open the folder in Visual Studio Code editor.
          
          Step 3 : Run "npm run dev" command in the terminal.
                    Start to use !!
## Tailwind_CSS
          Step 1 : Install NodeJs in pc (install LTS version).
          
          Step 2 : Open a new folder in Visual Studio code editor.
          
          Step 3 : Open terminal window.
          
          Step 4 : Run "node -v" command to confirm NodeJs is intalled properly.
          
          Step 5 : Run "npm init -y" command to create a package.json file
          
          Step 6 : Run "npm install -D tailwindcss" to install Tailwind css
          
          Step 7 : Run "npx tailwindcss init" command to crete a tailwind.config.js file
          
          Step 8 : Select tailwind.config.js file and edit the content: [], as content: [["./dist/*.{html,js}"],
          
          Step 9 : Create a new folder as "src" and create a new file as "input.css" and type "@tailwind base; @tailwind components; @tailwind utilities;" in "input.css" file.

          Step 10 : Run "npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch" command to create a dist folder with "output.css" file
          
          Step 11 : Create "index.html" file in dist folder along with the output.css file
          
          Step 12 : link the output.css by using "<link rel="stylesheet" href="output.css">" command in head of the index.html file.
                    check by using the class in tailwindcss Eg:(<h1 class="bg-green-200 ">Hello Tailwind !!!</h1>)
          Step 13 : Once again Run "npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch" command 
                    If it is not working - Press Ctrl+c and type "y" and give enter and once again run the step 13 command.
