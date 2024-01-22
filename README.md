## How to install tailwind css for production

step1- run the following command

``` npm init -y  ```

```npm i -D tailwindcss ```

```npx tailwindcss init ```

```npx tailwindcss -i ./src/input.css -o ./src/output.css --watch```

```create src/input.css and paste folowing lines then it will create output.css```

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

```
in tailwind.config.js
content: ["*.{html,js}"],
```

```now enjoy tailwind for prduction in your project```

```  "build":"npx tailwindcss -i ./src/input.css -o ./src/output.css --watch"
npm run build and enjoy ......
```