# Vamshi Reddy portfolio

A one-page data engineering portfolio. The source page is `index.html` in the GitHub repository; no framework or build step is needed.

## What each part does

1. **`<!doctype html>` and `<html lang="en">`** tell browsers to use modern HTML and identify the page language for assistive technology.
2. **The `<head>`** contains the browser tab title, mobile viewport settings, a short search description, and the page colors.
3. **The `<style>` block** controls typography, spacing, cards, buttons, and the mobile layout. Color variables near the top make the palette easy to change.
4. **The header navigation** links to section IDs such as `#projects`. These jump to sections on the same page.
5. **The introduction** explains the work quickly. The résumé button opens the existing `resume.docx` in this repository.
6. **Skills, experience, project, and background** organize the existing portfolio information for recruiters. Edit the text in the matching HTML section when your details change.
7. **The contact links** open email, LinkedIn, and GitHub. The form posts to the Formspree endpoint already used by the old page; verify that endpoint in your own Formspree account before relying on it for incoming messages.
8. **The footer script** changes the year automatically. It is the only JavaScript on the page.
9. **The `@media` rules** stack columns on narrow screens. The focus styles, labels, skip link, and reduced-motion rule help keyboard and assistive-technology users.

## Edit it yourself on GitHub

1. Open `index.html` in this repository and click the pencil icon (**Edit this file**).
2. Search for the visible text you want to change. Keep opening and closing tags intact.
3. Use the **Preview** tab to review your edit, then click **Commit changes**.
4. To update your résumé, upload a new `resume.docx` with the same name, or change the résumé link in `index.html` if the filename changes.
5. The legacy `profile.html` redirects to the main page. Make content changes in `index.html` only.

## Host from GitHub Pages, if you choose to use it

Open this repository's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. GitHub will show the website URL in Pages settings when publication finishes. `index.html` at the repository root is the entry page. Future commits to `main` then update that GitHub Pages site. The separate Sites-hosted copy requires its own publication when you change GitHub content.

## Content to check before sharing

- Confirm the experience dates, degree, awards, contact email, LinkedIn URL, and résumé are current.
- Send yourself a test message through the contact form and confirm it reaches your Formspree inbox.
- Open the page on both a phone and a desktop browser.
