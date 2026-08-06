# HireNeighborly

Parent site and community page templates.

Live community: lakewoodneighbors.com

## Structure

public/ is the deploy directory. Everything in it is served as a static asset.
public/index.html is the parent landing page at hireneighborly.com
wrangler.toml names the Worker and points Cloudflare at the public folder.

## Deploying

Push to main. Cloudflare Workers Builds runs npx wrangler deploy, and the site is live in about a minute. No manual uploads.
