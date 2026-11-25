# McKenna Consulting Engineers: website preview

Static site, no build step. Serve the folder as it is (for example GitHub Pages from the repo root).

## Files

- `index.html`: home
- `projects.html`: projects by sector
- `about.html`: the practice and team
- `contact.html`: contact details and enquiry form
- `images/`: 13 JPEGs used by the pages

All links and image paths are relative, so the site works from a subfolder as well as a domain root. Fonts (Barlow, Barlow Condensed) load from Google Fonts.

## Things to know before this goes anywhere public

- **Preview only.** Every page carries `<meta name="robots" content="noindex, nofollow">` so search engines skip it. Remove that line only when the real site launches.
- **Photos are stock stand-ins** from Unsplash. None shows the actual project. The six team portraits (`images/team-1.jpg` to `team-6.jpg`) are stock models shown under real staff names and must be replaced with real portraits before launch.
- **The enquiry form does not send anything.** It validates name, email and message and shows a confirmation, but there is no backend. Connect it to a form service or mail handler before launch.
- **The header mark and wordmark are stand-ins** for the firm's real logo.
- Copy was rewritten from the firm's current site (mckennace.com), which is dated 2023. Team and project details should be confirmed with the firm.
