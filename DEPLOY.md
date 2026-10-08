TOOLORA V1.1 (compact design)

Folder layout:
- index.html + one .html file per calculator
- source/ (design + logic master copies, used by Claude to rebuild pages; not needed on the live site)
- sitemap.xml, robots.txt -> for Google

Before going live:
1. Choose your domain, then replace YOUR-DOMAIN.com in every file (ask Claude to do it for you).
2. Upload this folder to a GitHub repository.
3. Connect the repository to Netlify (or Cloudflare Pages). Publish directory: root. No build command.
4. Add the custom domain and enable HTTPS.
5. Submit sitemap.xml in Google Search Console.

GPA/CGPA use a 5.0 scale: A=5, B=4, C=3, D=2, E=1, F=0.
Policy: no interest-based calculators (loans, mortgages, compound interest, etc.).
