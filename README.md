# marblepro.ae apex redirect

GitHub Pages site for the bare domain `marblepro.ae`. Every URL is sent to the
same path on `https://www.marblepro.ae`, which is hosted on Cloudflare Pages.

The domain's nameservers are at Hostinger and cannot be moved to Cloudflare
yet, and Cloudflare Pages only serves an apex domain whose zone is on
Cloudflare. So the apex points here (GitHub Pages A records) and this page
forwards visitors to www.

Once the nameservers move to Cloudflare, replace this with a Cloudflare
redirect rule and delete this repository.
