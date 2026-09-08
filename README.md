# dotanddashsensory.com

Static site for Dot & Dash Sensory. Two pages, no build step, no dependencies.
Both HTML files are fully self-contained: CSS and both webfonts are embedded,
so there are zero external requests.

## Deploy (GitHub Pages)

Upload these six files to the ROOT of a public repo:

    index.html
    methodology.html
    robots.txt
    sitemap.xml
    llms.txt
    CNAME

Then Settings > Pages > Deploy from a branch > main > / (root).

The CNAME file sets the custom domain automatically.

## DNS (at GoDaddy)

Four A records, Name @, TTL 600:

    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153

One CNAME, Name www, value: YOURUSERNAME.github.io

## Before publishing

1. Replace REPLACE placeholders with real YouTube / Pinterest handles
   (5 occurrences in index.html, 2 in methodology.html)
2. Fill every red dashed value on methodology.html with real pipeline numbers
3. Add primary research sources to the Sources section
4. Delete the red draft bar at the top of both files
