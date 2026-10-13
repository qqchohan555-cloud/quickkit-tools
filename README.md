# QuickKit Tools

A responsive, premium-dark static website with 9 browser-based utilities. Built with plain HTML, CSS, and JavaScript for free GitHub Pages hosting.

## Included tools
- Age calculator
- Percentage calculator (three modes)
- BMI calculator
- Word and character counter
- Case converter
- Password generator
- Tip calculator
- Loan payment estimator
- Text cleaner

## Files
- `index.html` — homepage and tool dialogs
- `style.css` — responsive dark theme
- `script.js` — tool logic and filtering
- `about.html`, `privacy.html`, `terms.html`, `contact.html` — starter information pages
- `robots.txt` — crawler defaults
- `ads.txt` — placeholder notes for future AdSense setup

## Publish on GitHub Pages
1. Create a **public** repository, for example `quickkit-tools`.
2. Upload every file in this folder to the repository root. Make sure `index.html` is in the root, not inside another nested folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then save.
6. Wait for the Pages deployment to finish. Your URL will look like `https://YOUR-USERNAME.github.io/quickkit-tools/`.

Official guide: https://docs.github.com/en/pages/quickstart

## Before you apply for AdSense
- Replace the contact placeholder in `contact.html`.
- Review and adapt the privacy and terms pages so they accurately describe your real setup and meet applicable requirements.
- Add original, useful explanatory content for each tool, not just the interface.
- Test the site on mobile and desktop, fix broken links, and confirm all pages work.
- Apply through AdSense and wait for site/account review. Approval is not guaranteed.
- Do not paste an invented publisher ID. Only add your real AdSense code after Google gives you the correct code and the site is eligible/approved.

### Ad placement
The homepage contains clearly labelled ad placeholders. They do not display ads or generate revenue until you add valid ad code. When approved, insert the official AdSense code supplied in your account and follow current Google policy.

### Important limitations
- GitHub Pages serves static files. There is no server-side runtime, database, or secret storage.
- The Google Fonts import requires internet access; system fonts will be used if it fails.
- This project is a starter site, not a guarantee of search traffic or AdSense approval.
- BMI, loan, and other calculation results are estimates and should be independently verified before important decisions.
