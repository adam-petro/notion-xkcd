# notion-xkcd

Simple vanilla HTML + CSS + JS that fetches the daily [XCKD](https://xkcd.com/) comic. The primary use is for users of Notion who would like to embed the daily XKCD comic to their landing page (or whatever the main 
dashboard is called).  

## A note on proxies
Due to the [same-origin](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy) browser policy, this widget needs a proxy to fetch data from a different origin. [Random_Comic_Generator](https://github.com/AdityaTiwari2102/Random_Comic_Generator) is used for that purpose. 

## How to embed to Notion
*To host this simple widget as a website, I use [CloudFlare pages](https://pages.cloudflare.com/). The deployment I am running is a free tier one with seeminly no limits on the amount of requests. Should this ever change, you can simply clone the source code and host it yourself of CloudFlare pages, Netlify or any other alternative.*

1. Go to the page in your Notion where you'd like the widget to be embedded.
2. Enter the `/embed` command.
3. Paste in the URL of the hosted website, i.e. `https://notion-xkcd.pages.dev`.
4. Profit.
