## X Clone made only using Tailwind CSS

## Setting up Tailwind CSS

Step 1: Run the following commands
```
npm install -D tailwindcss
npx tailwindcss init
```

Step 2: Update tailwind.config.js file to include:
```
content: ["*.html"]
```

Step 3: Create src/input.css to include:
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
