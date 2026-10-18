# One Stop Code landing page

This is the cleaned, static HTML/CSS version of the One Stop Code HTML and CSS course landing page.

## Preview locally
Open `index.html` in a browser. To use a local server, run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a new public repository on GitHub (for example, `one-stop-code`).
2. Upload `index.html` to the repository root and commit the changes.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will be shown in the Pages settings.

The page uses Google Fonts when internet access is available and falls back to system fonts otherwise. Course dates, prices, payment number, WhatsApp numbers, and course details have been retained from the supplied design.


## Jotform registration form
The registration form is embedded in `index.html` using an iframe: https://form.jotform.com/262903123851049

If you update the form in Jotform, those changes should appear in the embedded version automatically. Test the form after publishing.


Registration uses a direct link to the Jotform form (no embedded iframe): https://www.jotform.com/262903123851049
