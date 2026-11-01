THE NORHANS WEBSITE

index.html = the whole website (open it in a text editor to change text).
images/    = logo and photos used by the page.

BOOKING
Visitors fill the booking form and the request opens in your WhatsApp.
The owner dashboard only works on the claude.ai link, not on your own domain.
To block dates and set prices on your own domain, edit this line in index.html:
<script type="application/json" id="state">{"booked":["2026-12-10"],"cfg":{...}}</script>
"booked" = blocked dates (YYYY-MM-DD). "cfg" = prices (services, person, loc, dep, pay, cur).

HOSTING
Upload the whole folder to Cloudflare Pages or Netlify, then connect your domain.
