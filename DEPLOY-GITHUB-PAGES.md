# 🚀 Deploy "One More Plate" to GitHub Pages (Free)

This guide hosts your website at a free address like:

```
https://YOUR-USERNAME.github.io/one-more-plate/
```

Later you can point **your own domain** (e.g. `onemoreplate.in`) to it.

---

## ✅ What you need
- A free **GitHub account** → https://github.com/signup
- The website files (this folder)

> No software to install. We'll upload through the GitHub website.

---

## STEP 1 — Create a GitHub account
1. Go to https://github.com/signup
2. Use your email (`hublihelp@gmail.com`), pick a username (e.g. `hublihelp`).
3. Verify your email.

Your site will later be at `https://<username>.github.io/<repo-name>/`.

---

## STEP 2 — Create a new repository
1. Go to https://github.com/new
2. **Repository name:** `one-more-plate`  (no spaces)
3. **Description:** (optional) "Food rescue website for Hubballi"
4. Set it **Public** ✅ (required for free Pages)
5. **Do NOT** tick "Add a README file".
6. Click **Create repository**.

---

## STEP 3 — Upload the website files
On the empty repo page:

1. Click **"uploading an existing file"** (or **Add file → Upload files**).
2. Open this `one-more-plate` folder on your PC.
3. Select **everything INSIDE the folder** and drag it into the browser:
   ```
   index.html
   .nojekyll
   README.md
   DEPLOY-GITHUB-PAGES.md
   css/            (the whole folder)
   images/         (the whole folder — includes the logo + favicons)
   ```
   ⚠️ Important: upload the **contents**, so `index.html` sits at the **top level** of the repo — not inside another folder.

   > `.nojekyll` may be hidden in Windows. In File Explorer: **View → Show → Hidden items**.
4. In "Commit changes" write: `Initial website upload`
5. Click **Commit changes**.

---

## STEP 4 — Turn on GitHub Pages
1. In your repo, click **Settings** (top menu).
2. Left sidebar → **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Under **Branch**, select **main** and folder **/ (root)**.
5. Click **Save**.
6. Wait 1–2 minutes, then refresh the page.
7. A banner appears: **"Your site is live at https://<username>.github.io/one-more-plate/"**

🎉 Done! Share that link.

---

## STEP 5 (LATER) — Use your own domain

### A. Buy a domain
Any registrar works:
- **Namecheap** (cheap, good)
- **GoDaddy**
- **Hostinger / BigRock / GoDaddy India**
- **Cloudflare** (great DNS, at-cost domains)

Example domains: `onemoreplate.in`, `hublihelp.org`, `onemoreplate.co.in`

### B. Add it in GitHub
1. Repo → **Settings → Pages → Custom domain**.
2. Type your domain (e.g. `www.onemoreplate.in`) → **Save**.
3. Tick **Enforce HTTPS** (wait a few minutes for it to become available).

### C. Add DNS records at your registrar
Go to your registrar's **DNS settings** and add:

**If using `www.yourdomain.com`:**
| Type | Name | Value |
|---|---|---|
| CNAME | www | `YOUR-USERNAME.github.io` |

**If using the root/apex `yourdomain.com`:**
| Type | Name | Value |
|---|---|---|
| A | @ | `185.199.108.153` |
| A | @ | `185.199.109.153` |
| A | @ | `185.199.110.153` |
| A | @ | `185.199.111.153` |

**Recommended:** use both — `www` via CNAME and apex via the 4 A records — so both work.

### D. Wait
DNS can take from **10 minutes to 24 hours**. Then your site loads on your own domain with HTTPS.

> GitHub automatically creates a file called `CNAME` in your repo with your domain. Don't delete it.

---

## 🔁 How to update the website later
1. Open the repo, click the file (e.g. `index.html`) → ✏️ pencil icon → edit → **Commit changes**.
2. Changes go live in ~1 minute.
3. Or use **Add file → Upload files** to replace files.

---

## 💡 Alternative: Netlify (even simpler)
1. Go to https://app.netlify.com/drop
2. Drag the `one-more-plate` folder onto the page.
3. Instantly live at a random URL. Add your custom domain in **Site settings → Domain management**.
