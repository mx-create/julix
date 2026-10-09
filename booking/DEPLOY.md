# booking.mxdesign.uk

Static booking-confirmation page for Julix (PDF confirmation, WhatsApp message, calendar block).
Files to deploy: `index.html`, `robots.txt` — upload both to the web root of the `booking` subdomain.

- Hosting: Hostinger (mxdesign.uk), subdomain folder usually `public_html/booking`
- DNS: Cloudflare zone mxdesign.uk, A record `booking` -> 31.220.110.86, DNS only (grey cloud) until SSL is installed
- After upload: Hostinger hPanel → Security → SSL → install free SSL for booking.mxdesign.uk
