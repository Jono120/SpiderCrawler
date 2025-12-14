# SpiderCrawler
> NOTE: this is a work in progress, documentation will be updated as it goes.

This started as a small project for doing basic link checking and JavaScript component checks

It uses a basic check through the site to surface what links and pages are connected to the domain being requested.


## Functions
1. Checks all the components for getting the URL from the user
2. Scans the given link from the base domain to that of the children
3. Checks website for a sitemap
4. Takes a given URL and begins its scan for a Sitemap
5. Scans the site for any internally hosted JavaScript components
6. Outputs information into their respective CSV files