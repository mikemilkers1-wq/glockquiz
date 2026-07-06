# GLOCK GmbH RoNation LARP — Find Your GLOCK Quiz

A complete static website for a fictional RoNation / Roblox nation-roleplay Glock GmbH showroom quiz.

## What is included

```text
index.html
assets/
  css/styles.css
  js/app.js
  img/brand-mark.svg
  img/world-map.svg
README.md
```

## How to upload to GitHub Pages

1. Create a new GitHub repository.
2. Upload the full contents of this folder, not just the ZIP file.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root` folder.
6. Save. GitHub will provide your public website link after deployment.

## How to edit the quiz

Open `assets/js/app.js`.

- Edit `models` to change result names, descriptions, and bullet points.
- Edit `questions` to change quiz questions and answer scoring.
- Each answer has `weights`, for example:

```js
weights: { g17: 3, g19: 2 }
```

That answer gives 3 points to GLOCK 17 and 2 points to GLOCK 19.

## Important note

This website is written as an unofficial fictional roleplay page for RoNation LARP. It is not affiliated with or endorsed by the real GLOCK company. The recommendations are for in-game character flavor only and are not real-world purchasing or safety advice.
