# Flightcheck
Flightcheck for website release.

## Dev Essentials
- favicon
- check markup (https://validator.w3.org/)
- check accesibility (http://wave.webaim.org)
- can you navigate the site by keyboard?
- does the site work and make sense without styling?
- does the site work and make sense without javascript?
- does the site work and make sense on every device?
- does the printstyling make sense? It's also used for saving to PDF!
- does the site make sense on a screenreader?
- is a sitemap.xml being generated or has it been added manually?

## Deployment
- choose www/non-www and redirect the other
- are there aliases for the domain and do they work?
- is the .htaccess in order?
- security check: is everything that should not be accessible not accessible? Dev resources etc..

## Migrating a site?
- make old content available (when applicable with 301 redirects)

## Functionality
- check if forms store data or send mail as expected
- do forms keep data if you reload or switch page?
- check all filter pages if applicable
- fix broken links (https://validator.w3.org/checklink)
- does a search functionality return sensible results?

## Optimisation
- Pagespeed 90+ (https://developers.google.com/speed/pagespeed/insights/)
- Are images optimised?
- Is there a javascript strategy?

## Social media optimisation & SEO
- Do share buttons work?
- Open Graph tags (http://ogp.me, check them: https://developers.facebook.com/tools/debug/)
- Google Analytics or some other analytics needed?
- Google Search Console (and integration with Google Analytics) if applicable
- Apply schema.org markup where applicable https://schema.org/
