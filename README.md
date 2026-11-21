# YardLink starter website

This is a mobile-friendly front-end prototype for YardLink.

## Included
- Homeowner service request form
- Landscaper plan cards: Starter $29.99, Professional $49.99, Business $89.99
- Landscaper registration demo
- Local demo lead center

## Important limitations
This is a front-end prototype. It stores demo information in the current browser only.
It does NOT yet provide shared accounts, cross-device lead delivery, secure subscription enforcement,
or payment processing. Do not collect real customer information until a secure backend is connected.

## Free GitHub Pages hosting
1. Create a public GitHub repository named `yardlink`.
2. Upload `index.html` to the repository's top level (not inside another folder).
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch `main`, folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

GitHub Pages provides static hosting. To make the marketplace truly multi-user, connect a backend
such as Supabase and implement authenticated access plus server-side authorization before launch.
