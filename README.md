# Bot Bot Bot Sahur — ECE 5 UCSD Spring 2026

Portfolio website for our ECE 5 autonomous car project.  
**Team:** Vela B. · Vikram K. · Peter S. · Anthony Z.

## Quick edits

### Change team/robot name
Open `index.html` and find `ECE 5 Robot` in the `<nav>` and hero section.

### Add photos
1. Drop image files into `assets/images/`
2. In `index.html`, find the gallery section and replace a placeholder block with:
```html
<div class="gallery-item">
  <img src="assets/images/your-file.jpg" alt="Short description" />
  <span class="caption-overlay">Caption text</span>
</div>
```

### Add a video
- **YouTube**: replace the `<div class="video-placeholder">` block with:
  ```html
  <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen title="Robot demo"></iframe>
  ```
- **Local file**: put the file in `assets/videos/` and use:
  ```html
  <video controls><source src="assets/videos/demo.mp4" type="video/mp4" /></video>
  ```

### Update the build log
Copy a `<div class="log-entry">` block in the Build Log section and update the date, title, description, and status badge (`status--done`, `status--progress`, `status--planned`).

### Add team members
Edit the team cards in the `#team` section. To use a real photo:
```html
<div class="team-avatar"><img src="assets/images/name.jpg" alt="Name" /></div>
```

## Deploy to GitHub Pages
1. Push to GitHub
2. Go to Settings → Pages → Source: `main` branch, `/ (root)`
3. Your site will be live at `https://<username>.github.io/<repo-name>/`
