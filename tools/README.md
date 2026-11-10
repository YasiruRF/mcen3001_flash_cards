# Rebuilding tailwind.css
index.html uses a pre-built stylesheet. After changing classes in index.html:

    cd tools && npm i tailwindcss@3 && npx tailwindcss -c tailwind.config.js -i input.css -o ../tailwind.css --minify
