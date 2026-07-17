# Birthday website

A single-page birthday gift site: greeting → photos → flowers → song → letter.
It's one self-contained `index.html` file — no build step, no server needed.

## Before you send it

- Open `index.html` in a browser and click through the photo frames to add real photos (they load locally in your browser).
- Edit the greeting text and the letter text directly in `index.html` — search for `Hello there` and `Dear [her name]`.

## Put it on GitHub and host it for free (GitHub Pages)

1. Go to https://github.com/new and create a new repository (e.g. `her-birthday-site`). Keep it **public** if you want free Pages hosting.
2. On your computer, open a terminal in this folder and run:
   ```
   git init
   git add .
   git commit -m "birthday site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, open the repo → **Settings** → **Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

That link is what you can send her — it works on any phone, no app needed.
