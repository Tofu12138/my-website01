# DebyGames Website

Static website for `debygamesfunfact.com`, designed for GitHub Pages and App Store Connect URL fields.

## App Store URLs

- Support URL: `https://debygamesfunfact.com/support.html`
- Marketing URL: `https://debygamesfunfact.com/`
- Privacy Policy URL: `https://debygamesfunfact.com/privacy-policy.html`
- Privacy Choices URL: `https://debygamesfunfact.com/privacy/choices/`

## GitHub Pages deployment

1. Create a GitHub repository, for example `debygamesfunfact`.
2. Upload all files in this folder to the repository root on the `main` branch.
3. In GitHub, open **Settings** > **Pages**.
4. Choose **Deploy from a branch**, then select `main` and `/(root)`.
5. Under **Custom domain**, enter `debygamesfunfact.com`.
6. At your domain provider, create the DNS records GitHub Pages asks for. For an apex domain, GitHub Pages commonly uses these `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Create a `CNAME` record for `www` pointing to your GitHub Pages host, such as `YOUR-GITHUB-USERNAME.github.io`.
7. Wait for DNS verification to complete, then enable **Enforce HTTPS** in GitHub Pages.
8. Open every final URL above on desktop and mobile before using it in App Store Connect.

## Required before App Store submission

- Configure working email inboxes or forwarding for `support@debygames.freeqiye.com` and `privacy@debygames.freeqiye.com`.
- Confirm every app using this policy includes only the advertising SDKs listed in the Privacy Policy.
- If an app is directed to children, uses accounts, subscriptions, in-app purchases, analytics, crash reporting, or collects additional data, update the Privacy Policy before submission.
- Use final HTTPS URLs in App Store Connect, not GitHub preview URLs.
