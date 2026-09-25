# RS School CV (public mirror)

Static copy of the [RS School](https://rs.school/) public CV page, without the app shell (navigation, login, etc.). The authoritative CV lives in the RS app at [https://app.rs.school/cv/ad0f0ca9-a33c-41eb-a281-b7e8ac46817c](https://app.rs.school/cv/ad0f0ca9-a33c-41eb-a281-b7e8ac46817c) (sign-in required).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages

1. Push this repository to GitHub (`mark-pribylnov/RSS-CV`).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions** (workflow included) or **Deploy from branch** → branch `main` → folder `/ (root)`.
4. After deployment, the site is available at `https://mark-pribylnov.github.io/RSS-CV/`.

## Links

External links (certificates, GitHub, LinkedIn, Telegram, email) match the original RS School CV. Certificate URLs point to `app.rs.school` and open without this site’s login.

## Profile photo

`assets/avatar.jpg` is your LinkedIn profile photo (saved locally so GitHub Pages does not depend on LinkedIn CDN expiry).
