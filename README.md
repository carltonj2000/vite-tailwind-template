# Vite TailwindCSS Template

## Creation History

```bash
npm init @vite/app
cd "directory created above"
npm i
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest\n
npx tailwindcss init -p # -p does post css at same time
```

After above:

- to tailwind.config.js add
  - mode: "jit"
  - purge: ["./index.html"]
- in style.css add 3 lines @tailwind base/components/utilities
- index.html add relative link to css file
