SHRIMPS TOWN — WEBSITE + FREE LAUNCH GUIDE

WHAT IS INCLUDED
- Premium responsive aquarium storefront
- Search + category filters
- Product detail modal
- Multiple image support per product
- Stock count and Out of Stock state
- Cart and quantities
- WhatsApp checkout
- SEO title/description
- robots.txt + sitemap.xml

FIRST: EDIT index.html
Find "EASY EDIT AREA" in index.html and update:
1. WHATSAPP_NUMBER = your WhatsApp number with country code, no + or spaces.
2. address
3. helpline
4. products (name, category, price, stock, images, description)

IMAGE EXAMPLE
images: [
  "images/red-shrimp-1.jpg",
  "images/red-shrimp-2.jpg",
  "images/red-shrimp-3.jpg"
]

FREE PUBLIC LAUNCH WITH GITHUB PAGES
1. Create a free GitHub account at https://github.com/
2. Create a new PUBLIC repository called: shrimps-town
3. Upload all files from this folder:
   - index.html
   - robots.txt
   - sitemap.xml
   - images/ folder
4. Open repository Settings > Pages.
5. Under Build and deployment, choose "Deploy from a branch".
6. Select the main branch and / (root), then Save.
7. GitHub will give you a public URL similar to:
   https://YOUR-USERNAME.github.io/shrimps-town/
8. Replace YOUR-USERNAME in robots.txt and sitemap.xml with your actual GitHub username, then upload those two files again.
9. Test the public website on your phone using mobile data.

GOOGLE SEARCH
1. Open Google Search Console: https://search.google.com/search-console/
2. Add your exact GitHub Pages URL as a URL-prefix property.
3. Verify ownership using one of the methods Google offers.
4. Submit:
   https://YOUR-USERNAME.github.io/shrimps-town/sitemap.xml
5. Use URL Inspection in Search Console and request indexing for the home page.
6. Google indexing is not instant. Search visibility can take time and is not guaranteed immediately.

IMPORTANT ABOUT "FREE"
- GitHub Pages hosting can be free with GitHub Free.
- The default github.io address is free.
- A custom .com/.in domain is normally NOT free; it requires buying a domain.
- You do not need a paid domain to make the website publicly accessible.

WHATSAPP
The website does NOT take online payment. It sends the selected order to WhatsApp.
Replace WHATSAPP_NUMBER before publishing.

SECURITY / PRIVACY
Do not put passwords, payment card details, API secrets, or other private credentials inside index.html or the public repository.
