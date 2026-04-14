# CINE 366 Final Website

Portfolio site displaying broadcast journalism pieces: VO, VOSOT, Social Media Story, and Package.

## Hosting on GitHub Pages

1. Push this repo to GitHub (if not already):
   ```
   git remote add origin https://github.com/YOUR_USERNAME/cine-366-final-website.git
   git push -u origin main
   ```

2. Go to your repo on GitHub → **Settings** → **Pages**

3. Under **Source**, select **Deploy from a branch** → choose `main` branch, `/ (root)` folder → **Save**

4. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/cine-366-final-website/
   ```
   (GitHub may take ~1 minute to deploy)

## To add the Package video later

Open `index.html` and replace the `<div class="coming-soon">` block in the Package section with:
```html
<div class="video-wrapper">
  <iframe
    src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
    title="Package"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>
```
