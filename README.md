# Free public legal pages for TikTok app registration

TikTok requires a **publicly accessible Terms of Service URL and Privacy Policy URL** that you control. `localhost` and local files cannot be used.

This folder contains ready-to-publish static pages for that purpose. It costs **RM0** using GitHub Pages.

> **Assumption:** the pages currently use GitHub username `Irfan` (taken from your Windows profile). If your real GitHub username is different, replace every `Irfan` in the three HTML files and in the URLs below with your actual username before uploading.

## 1. What to paste into TikTok

After publishing (steps below), enter these URLs:

| TikTok field | URL |
|---|---|
| Website URL / App website | `https://Irfan.github.io/multipost-studio-site/` |
| Terms of Service URL | `https://Irfan.github.io/multipost-studio-site/terms.html` |
| Privacy Policy URL | `https://Irfan.github.io/multipost-studio-site/privacy.html` |

If TikTok also asks for a **Privacy Policy URL** for a second platform (Web/Desktop vs Mobile), use the same privacy URL for both.

## 2. Publish with GitHub Pages (free, browser only)

Git and GitHub CLI are not installed on this PC, so use the website:

1. Go to https://github.com/ and sign in (create a free account if needed).
2. Click **+ → New repository**.
   - Name: `multipost-studio-site`
   - Visibility: **Public** (required for free GitHub Pages)
   - Leave “Add a README file” unchecked.
3. Click **Create repository**.
4. On the new repository page click **uploading an existing file**.
5. Drag in these three files from this folder:
   - `index.html`
   - `terms.html`
   - `privacy.html`
6. Click **Commit changes**.
7. Go to **Settings → Pages** (left sidebar).
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: **/ (root)**
   - Click **Save**.
8. Wait 1–2 minutes, then open the website URL from the table above in a browser. If it loads, the ToS and Privacy links will work too.

## 3. TikTok URL verification (if requested)

1. In the TikTok app page, click **URL properties**.
2. Choose **Verify by URL prefix** (simplest with GitHub Pages).
3. Download the signature file TikTok gives you.
4. Back on GitHub, click **Add file → Upload files** and upload that signature file to the same repository; commit.
5. Wait until `https://Irfan.github.io/multipost-studio-site/<signature-file-name>` opens in a browser, then click **Verify** in TikTok.

## 4. If you already have a website

Skip GitHub. Upload these three HTML files anywhere you control and paste those real public URLs into TikTok. TikTok only checks that the pages are reachable and honestly describe the app.

## 5. Important

The templates describe the application honestly: it is a free, local, self-hosted Windows tool. Do not publish placeholder text, fake companies, or contact addresses you cannot monitor. The contact method used here is a GitHub Issues link, which is real once the repository exists.
