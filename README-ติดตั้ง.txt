K-ROOF SEO PACKAGE

Package contents:
- index.html: current site source with product cards linked to separate SEO pages for the 12 built-in product names.
- products/: 12 static product detail pages with Thai titles, descriptions, canonical URLs, Product structured data, specs where available, and LINE/phone contact.
- sitemap.xml: homepage plus product detail pages.

Deployment steps:
1. Download and unzip this package.
2. In GitHub repository Sarawut0909/k-roof-website, replace the root index.html with this index.html.
3. Upload the entire products folder (including all .html files) to the repository root.
4. Replace root sitemap.xml with the sitemap.xml in this package.
5. Commit changes and wait for GitHub Pages deployment to finish.
6. In Google Search Console, submit https://หลังคาเครูฟ.com/sitemap.xml (or the punycode version shown in the address bar).
7. Inspect the homepage and a few product URLs, then click Request indexing.

Important:
- Do not replace or delete config.js or CNAME. Keep existing GitHub Pages/DNS settings.
- This package is based on the latest index1.html file saved in the prior conversation. Before replacing the live file, compare it with the current GitHub index.html if there have been newer edits after Oct 13.
- Product photos stored only in a browser's IndexedDB are not automatically included in Google-searchable product pages. To make images available to all visitors and Google, upload them to the site's shared storage and add them to these product pages.
- Google indexing is not guaranteed or instant.
