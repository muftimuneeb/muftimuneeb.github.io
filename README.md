# Portfolio: Muneeb Ur Rehman

Static site, no build step. Files:

- `index.html`: the whole site (HTML, CSS, JS)
- `pic-cutout.webp`: hero portrait with the background removed; `pic.jpg`: your original photo; `avatar.jpg`, `favicon.png`: small versions cut from it
- `Muneeb_Ur_Rehman_Resume.docx`: file behind the Download CV buttons
- `robots.txt`

## Before deploying
1. After you have your domain, change `og:image` in the `<head>` to the full URL, e.g. `https://yourname.com/avatar.jpg`, so link previews show your photo.

## Deploy
- Netlify: drag this folder onto app.netlify.com/drop
- GitHub Pages: push all files to a repo, then Settings > Pages > branch `main`, folder `/ (root)`
- Vercel or Cloudflare Pages: import the repo or upload the folder

Keep all files in the same folder so the images and CV link work.
