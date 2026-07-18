# ronbajrami.com

Personal portfolio. Single static HTML file, no build step.

## Hosting on GitHub Pages

1. Repo Settings > Pages > Source: "Deploy from a branch" > Branch: main, folder: / (root) > Save
2. Settings > Pages > Custom domain: enter ronbajrami.com, save, and check "Enforce HTTPS" once it verifies

## DNS records (at your domain registrar)

| Type  | Name | Value                   |
|-------|------|-------------------------|
| A     | @    | 185.199.108.153         |
| A     | @    | 185.199.109.153         |
| A     | @    | 185.199.110.153         |
| A     | @    | 185.199.111.153         |
| CNAME | www  | theronbajrami.github.io |

Delete the old A/CNAME records pointing to 10WEB first. DNS can take up to an hour to propagate.

## Contact form

Powered by FormSubmit. Submit the form once yourself after the site is live and click the confirmation link FormSubmit emails to ronbajrami2005@gmail.com. After that it forwards all messages automatically.
