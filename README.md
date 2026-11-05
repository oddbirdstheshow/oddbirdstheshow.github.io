# data branch

Holds `count.json`, the number of confirmed waitlist sign-ups in Kit. The
"Update waitlist counter" workflow on `main` refreshes it every 30 minutes, and
the home page reads it to show how many birds are still at large. Nothing here
is published by GitHub Pages; the page reads it from raw.githubusercontent.com.
