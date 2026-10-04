# lukegustafson.com

Signup **request** page for Luke's Leadership Briefing. Static HTML served by GitHub Pages.

- `index.html`: the page (inline CSS and JS, no build step).
- `banner.jpg`: 1200x450 banner, copied from `luke-gus/tn-briefing-assets`.
- Form backend: [FormSubmit](https://formsubmit.co) AJAX endpoint. Each request is emailed to Luke for personal review. Nobody is added to any list automatically.
- `golive/CNAME`: staged custom-domain file. It is deliberately **not** in the site root yet, so the github.io preview keeps working. At go-live, move it to the repo root (or set the custom domain in Settings > Pages).
- `robots.txt` and the `noindex` meta tag keep the page out of search engines. Remove both if Luke wants it indexed.
