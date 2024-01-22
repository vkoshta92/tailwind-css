## How to install tailwind css for production

step1- run the following command

``` npm init -y  ```

```npm i -D tailwindcss ```

```npx tailwindcss init ```

```npx tailwindcss -i ./src/input.css -o ./src/output.css --watch```

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

```
in tailwindconfig
content: ["*.{html,js}"],
```

```now enjoy tailwind for prduction in your project```