AIQOLA Website v1.8.1 — Clean URL Hotfix

Why:
The previous /aiqola-intelligence/ route depended on a nested folder:
aiqola-intelligence/index.html.
When uploading from mobile GitHub, that folder structure may not be created,
causing Vercel 404 NOT_FOUND.

Fix:
- AIQOLA Intelligence page is now a flat file: aiqola-intelligence.html
- vercel.json rewrites /aiqola-intelligence -> /aiqola-intelligence.html
- Browser-visible URL stays clean:
  https://aiqola.vercel.app/aiqola-intelligence
- Old /intelligence.html redirects to the clean URL.
- All v1.8 design revisions are retained.

Upload ALL 5 files to the ROOT of the GitHub repository:
1. index.html
2. aiqola-intelligence.html
3. intelligence.html
4. vercel.json
5. README.txt

Do not upload a folder for this hotfix.
