ARM WRESTLE SHOWDOWN — FREE LANDING PAGE

Files: index.html, logo.png, favicon.png, CNAME

GitHub Pages deployment:
1. Sign in at github.com and create a PUBLIC repository named armwrestleshowdown-site.
2. Upload all four files to the repository root (not the ZIP itself).
3. Go to Settings > Pages, select Deploy from a branch, choose main and /(root), and save.
4. Under Settings > Pages, set Custom domain to armwrestleshowdown.com (if not already picked up from CNAME).
5. In Namecheap > Domain List > Manage > Advanced DNS, set A records for @ to:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   Remove conflicting parking or redirect records for @.
6. Add a CNAME record for www pointing to YOUR-GITHUB-USERNAME.github.io (replace placeholder with actual GitHub username).
7. Wait for DNS propagation, then in GitHub Pages enable Enforce HTTPS when available.
8. Test both https://armwrestleshowdown.com and https://www.armwrestleshowdown.com.

Important: GitHub Pages on a free plan requires a public repository; avoid uploading private details or secrets. Confirm the social profile links resolve to your intended accounts before sharing the site widely.
