# tailwindSandbox

## Cara 1 Menginstall Tailwind CSS

    npm init -y

    npm install -D tailwindcss

    npx tailwindcss init

    tambahin alamat file index ke tailwind.config.js

    bikin file tailwind.css, isinya [@tailwind base;@tailwind components;@tailwind utilities;]

    tambahin ["dev": "tailwindcss -i ./tailwind.css -o ./style.css --watch"] ke package.json, di bagian scripts

    tambahin <link rel="stylesheet" href="style.css"> ke index.html

### mulai

    npm run dev

## Cara 2 Menginstall Tailwind CSS

    add {
        <script src="https://cdn.tailwindcss.com"></script>
    } to index.html

    create file "tailwind.config.js"
