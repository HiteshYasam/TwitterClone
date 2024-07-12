# TwitterClone
Twitter Clone( FrontEnd) built with Tailwind CSS 

## Features

<li>Website is built with the help of TailWind CSS</li>
<li>Tailwind CSS is a great tool for quick production of websites</li>
<li>It does not use inline css its just a way of writing it compiles all the classes into output.css</li>
<li>Breakpoints are used similar to media queries to optimise for all kinds of devices</li>
<li>It copies the used css utilites and updates in output.css</li>
<li>Website load time is Normal as we are not using all the utilites in input.css</li>
<li>Additinally using vite can help in live re-loading</li>

## How to setup Tailwind CSS

Step 1: Run the following commands

``` 
npm install -D tailwindcss
npx tailwindcss init
```

Step 2: Update tailwind.conf.js file to include this line:
```
content: ["*.html"],
```

Step 3: create src/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4: Include the src/output.css file to your html

Step 5: Run the following command:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

