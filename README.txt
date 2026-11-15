OUROV — SEO support files

Files
-----
robots.txt
  Allows search-engine crawlers to access the public website and points them
  to the sitemap.

sitemap.xml
  Lists the canonical public URL: https://ourov.in/

Install
-------
1. Upload both files to the same public root directory as index.html.
2. They must be accessible at:
   https://ourov.in/robots.txt
   https://ourov.in/sitemap.xml
3. Do not place them inside an assets or subfolder.
4. After deployment, open both URLs in a browser to confirm they load.
5. Submit https://ourov.in/sitemap.xml in Google Search Console.

Notes
-----
The supplied website is a single-page website. Its internal sections use
fragment links (#work, #services, etc.), so they are not separate sitemap URLs.
The HTML already contains a canonical URL and an index,follow robots meta tag.
This sitemap lists only the canonical homepage and does not invent extra pages.
