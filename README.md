# PocPoc

The website of PocPoc, Marina and Fábio's party business in the Algarve: catering,
decoration, bouncy castles and entertainment for children's parties, christenings, baby
showers, adult birthdays and weddings.

- `index.html` the site, Portuguese first with an English switch
- `monta.html` the booking flow: build the party, see the exact price, request a quote
- `obrigada.html` the page customers get after a party: a few questions and an optional video
- `photos/` her photos and flyers

Static files, served by GitHub Pages. Quote requests and reviews go to Supabase with a
publishable key that can insert and cannot read. Source of truth and notes live in Adam's
PocPoc project folder; publish with `tools/publish.ps1` there.
