# hubot-cloudflare
Purge all files within a CloudFlare zone using Hubot and Slack integration.

<h3>Dependencies</h3>

This script requires the cloudflare4 npm package to run (https://www.npmjs.com/package/cloudflare4).

<code>npm install cloudflare4 --save</code>

<h3>Configuration</h3>
Configure your CloudFlare email address and CloudFlare API key within the options headers of the cloudflare.js script. Once this has been done, save the changes and upload it to your bot's scripts directory.

<h3>Usage</h3>
Type purge \<domain\> to purge all files within your website's zone. Your website must be set-up under your own CloudFlare account.
